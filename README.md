# util-games
current work red-lang games utilities testing

grab latest zip and latest red

![DUB](https://img.shields.io/dub/l/dub)
![LANG](https://img.shields.io/badge/-red-AE2528?style=plastic&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDIyLjAuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgMjAwIDIwMCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgMjAwIDIwMDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPgo8c3R5bGUgdHlwZT0idGV4dC9jc3MiPgoJLnN0MHtmaWxsOnVybCgjU1ZHSURfMV8pO30KCS5zdDF7ZmlsbDp1cmwoI1NWR0lEXzJfKTt9Cgkuc3Qye2ZpbGw6dXJsKCNTVkdJRF8zXyk7fQoJLnN0M3tmaWxsOnVybCgjU1ZHSURfNF8pO30KCS5zdDR7ZmlsbDp1cmwoI1NWR0lEXzVfKTt9Cgkuc3Q1e2ZpbGw6dXJsKCNTVkdJRF82Xyk7fQo8L3N0eWxlPgo8Zz4KCQoJCTxsaW5lYXJHcmFkaWVudCBpZD0iU1ZHSURfMV8iIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iNzIuNDI4NSIgeTE9Ijg4MC41NSIgeDI9Ijk5Ljk5NDEiIHkyPSI4ODAuNTUiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSAwIDAgMSAwIC04NTIpIj4KCQk8c3RvcCBvZmZzZXQ9IjAiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCQk8c3RvcCBvZmZzZXQ9IjEiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCTwvbGluZWFyR3JhZGllbnQ+Cgk8cG9seWdvbiBjbGFzcz0ic3QwIiBwb2ludHM9IjEwMCw1Ni4xIDEwMCwxIDcyLjQsNDEuOCAgIi8+CgkKCQk8bGluZWFyR3JhZGllbnQgaWQ9IlNWR0lEXzJfIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjEwMCIgeTE9Ijk0Mi43IiB4Mj0iMTYzLjMiIHkyPSI5NDIuNyIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxIDAgMCAxIDAgLTg1MikiPgoJCTxzdG9wIG9mZnNldD0iMCIgc3R5bGU9InN0b3AtY29sb3I6I0ZGRkZGRiIvPgoJCTxzdG9wIG9mZnNldD0iMC41ODM0IiBzdHlsZT0ic3RvcC1jb2xvcjojRkZGRkZGIi8+CgkJPHN0b3Agb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjojRkZGRkZGIi8+Cgk8L2xpbmVhckdyYWRpZW50PgoJPHBvbHlnb24gY2xhc3M9InN0MSIgcG9pbnRzPSIxMDAsNzIuNCAxMDAsMTI3LjYgMTAwLDEyNy42IDE2My4zLDk0LjYgMTM1LjcsNTMuOCAgIi8+CgkKCQk8bGluZWFyR3JhZGllbnQgaWQ9IlNWR0lEXzNfIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjEwMCIgeTE9Ijg4MC41NSIgeDI9IjEyNy41NzE1IiB5Mj0iODgwLjU1IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgMCAtODUyKSI+CgkJPHN0b3Agb2Zmc2V0PSIwIiBzdHlsZT0ic3RvcC1jb2xvcjojRkZGRkZGIi8+CgkJPHN0b3Agb2Zmc2V0PSIwLjYxMjEiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCQk8c3RvcCBvZmZzZXQ9IjEiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCTwvbGluZWFyR3JhZGllbnQ+Cgk8cG9seWdvbiBjbGFzcz0ic3QyIiBwb2ludHM9IjEwMCw1Ni4xIDEyNy42LDQxLjggMTAwLDEgICIvPgoJCgkJPGxpbmVhckdyYWRpZW50IGlkPSJTVkdJRF80XyIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSIxMDAiIHkxPSIxMDA0Ljg1IiB4Mj0iMTk5IiB5Mj0iMTAwNC44NSIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxIDAgMCAxIDAgLTg1MikiPgoJCTxzdG9wIG9mZnNldD0iMCIgc3R5bGU9InN0b3AtY29sb3I6I0ZGRkZGRiIvPgoJCTxzdG9wIG9mZnNldD0iMC41ODM0IiBzdHlsZT0ic3RvcC1jb2xvcjojRkZGRkZGIi8+CgkJPHN0b3Agb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjojRkZGRkZGIi8+Cgk8L2xpbmVhckdyYWRpZW50PgoJPHBvbHlnb24gY2xhc3M9InN0MyIgcG9pbnRzPSIxNzEuNCwxMDYuNyAxMDAsMTQzLjkgMTAwLDE0My45IDEwMCwxOTkgMTk5LDE0Ny41ICAiLz4KCQoJCTxsaW5lYXJHcmFkaWVudCBpZD0iU1ZHSURfNV8iIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iMSIgeTE9IjEwMDQuODUiIHgyPSIxMDAiIHkyPSIxMDA0Ljg1IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgMCAtODUyKSI+CgkJPHN0b3Agb2Zmc2V0PSIwIiBzdHlsZT0ic3RvcC1jb2xvcjojRkZGRkZGIi8+CgkJPHN0b3Agb2Zmc2V0PSIwLjU2MjkiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCQk8c3RvcCBvZmZzZXQ9IjEiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCTwvbGluZWFyR3JhZGllbnQ+Cgk8cG9seWdvbiBjbGFzcz0ic3Q0IiBwb2ludHM9IjEsMTQ3LjUgMTAwLDE5OSAxMDAsMTQzLjkgMjguNiwxMDYuNyAgIi8+CgkKCQk8bGluZWFyR3JhZGllbnQgaWQ9IlNWR0lEXzZfIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjM2LjciIHkxPSI5NDIuNyIgeDI9IjEwMCIgeTI9Ijk0Mi43IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEgMCAwIDEgMCAtODUyKSI+CgkJPHN0b3Agb2Zmc2V0PSIwIiBzdHlsZT0ic3RvcC1jb2xvcjojRkZGRkZGIi8+CgkJPHN0b3Agb2Zmc2V0PSIwLjU2MjkiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCQk8c3RvcCBvZmZzZXQ9IjEiIHN0eWxlPSJzdG9wLWNvbG9yOiNGRkZGRkYiLz4KCTwvbGluZWFyR3JhZGllbnQ+Cgk8cG9seWdvbiBjbGFzcz0ic3Q1IiBwb2ludHM9IjY0LjMsNTMuOCAzNi43LDk0LjYgMTAwLDEyNy42IDEwMCw3Mi40ICAiLz4KPC9nPgo8L3N2Zz4K)
