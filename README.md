# ECMAScript-worker-implementations
In ECMAScript Applications often diffrent workers are used wich are offering diffrent globals as context to isolate workloads this is a collection of the most often used once.

- web-context (Optional/additional JSDOM) (messaging)
  - web-worker https://github.com/developit/web-worker
  - fetch
  - service-worker
  - localstorage
  - indexDB
  - audiWorklet
  - Web Crypto
  - Web Streams
- worker th's (messaging)
- child_process 
- cluster (loadbalanced via shared nativ modules) 
