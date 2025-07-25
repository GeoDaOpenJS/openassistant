# Variable: geocoding

> `const` **geocoding**: `ExtendedTool`\<[`GeocodingFunctionArgs`](../type-aliases/GeocodingFunctionArgs.md), [`GeocodingLlmResult`](../type-aliases/GeocodingLlmResult.md), [`GeocodingAdditionalData`](../type-aliases/GeocodingAdditionalData.md), `object`\>

Defined in: [packages/tools/osm/src/geocoding.ts:51](https://github.com/geodaopenjs/openassistant/blob/0a6a7e7306d75a25dc968b3117f04cb7bd613bec/packages/tools/osm/src/geocoding.ts#L51)

## Geocoding Tool

This tool converts addresses into geographic coordinates (latitude and longitude) using OpenStreetMap's Nominatim service.

Example user prompts:
- "Find the coordinates for 123 Main Street, New York"
- "What are the coordinates of the Eiffel Tower?"
- "Get the location of Central Park"

## Example

```typescript
import { geocoding, GeocodingTool } from "@openassistant/osm";
import { convertToVercelAiTool } from '@openassistant/utils';
import { generateText } from 'ai';

generateText({
  model: openai('gpt-4o-mini', { apiKey: key }),
  prompt: 'What are the coordinates of the Eiffel Tower?',
  tools: {
    geocoding: convertToVercelAiTool(geocoding),
  },
});
```
