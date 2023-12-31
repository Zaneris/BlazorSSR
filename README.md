# BlazorSSR
Minimum required setup off the base templates to get Blazor SSR/United working with WASM and WS Components.

## Build with .NET 8

- `/` Home uses SSR, page comes as pre-rendered HTML
- `/weather` uses SSR + streaming to load the updated forecast after a delay
- `/FormDemo` uses SSR + the new enhanced form, doesn't use WASM or websockets and doesn't do a full page refresh on submission
- `/AutoCounter` uses WebSockets/Server on first load, downloads WASM files, uses WASM on second load
- `/WsCounter` uses Blazor Server for the counter component (websocket)
- `/WasmCounter` uses Blazor WASM for the component, downloads WASM files and runs client-side

Repo put together based off of demo by Daniel Roth: https://www.youtube.com/watch?v=QD2-DwuOfKM
