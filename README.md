# Real-Time Voice Inference - Daily Transport

> [!CAUTION]
> This Repository and corresponding package has moved! Check out the latest, now part of a larger suite of transports at [github.com/pipecat-ai/pipecat-client-web-transports](https://github.com/pipecat-ai/pipecat-client-web-transports/tree/main/transports/daily) and [@pipecat-ai/daily-transport](https://www.npmjs.com/package/@pipecat-ai/daily-transport)

[![Docs](https://img.shields.io/badge/documentation-blue)](https://docs.pipecat.ai/client/reference/js/transports/transport)
![NPM Version](https://img.shields.io/npm/v/@daily-co/realtime-ai-daily)

Daily transport package for use with `realtime-ai`.

## How to use

#### Install relevant packages

```bash
npm install realtime-ai @daily-co/realtime-ai-daily
```

#### Import and pass transport to your RTVI client
```typescript
import { RTVIClient } from "realtime-ai";
import { DailyTransport } from "@daily-co/realtime-ai-daily";

const rtviClient = new RTVIClient({
    transport: new DailyTransport(),
    // ... your RTVI config here
});

await rtviClient.connect();
```

###Documentation

Please refer to the RTVI documentation [here](https://docs.pipecat.ai/client/reference/js/introduction).