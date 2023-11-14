# BlazorSSR
Minimum required setup off the base templates to get Blazor SSR/United working with WASM and WS Components.

## Build with .NET 8

- `/` Home uses SSR, page comes as pre-rendered HTML
- `/weather` uses SSR + streaming to load the updated forecast after a delay
- `/WsCounter` uses Blazor Server for the counter component (web socket)
- `/WasmCounter` uses Blazor WASM for the component, downloads WASM files and runs client-side

Repo put together based off of demo by Daniel Roth: https://www.youtube.com/watch?v=QD2-DwuOfKM
