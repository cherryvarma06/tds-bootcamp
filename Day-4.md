---
---

--- Before Day-4 ---
I already knew that websites communicate over the internet using requests and responses, and I had heard of GET and POST methods before, but I never fully understood the differences between all HTTP methods or what status codes like 401 and 403 actually mean in practice.
---

## Day-4 Checklist

- [x] I know the 5 core HTTP methods (GET, POST, PUT, PATCH, DELETE) and what each is used for
- [x] I can read a status code and know what went wrong — e.g., 401 vs. 403 vs. 404 vs. 500
- [x] I can open Chrome DevTools Network tab, find a request, and inspect its headers, payload, and response
- [x] I can copy a browser request as a cURL command and run it in the terminal
- [x] I can change the `User-Agent` in the browser and see the change in the Network tab
- [x] I can use `curl` to make a GET request with query parameters and a POST request with a JSON body
- [x] I have a running FastAPI app with at least two endpoints (`GET /health` and `POST /echo`)
- [x] I can test my API using the Swagger UI at `/docs` and via `curl` from the terminal

--- After Day-4 ---
I learned these things as well, apart from the checklist-I now understand the full request-response cycle much more deeply, including how headers carry important metadata like authentication and content type. Using Chrome DevTools to inspect real network requests was eye-opening — I could see exactly what the browser sends and receives. Building a FastAPI app with working endpoints and testing it through Swagger UI made the whole concept of APIs feel very hands-on and real.
---

--- Feedback (Suggestions for the TDS Team) ---
This is my feedback-Day 4 was one of the most practical days so far. Connecting browser behavior to actual HTTP concepts using DevTools was a great teaching approach. Building a FastAPI app from scratch and immediately testing it with curl and Swagger UI made everything click. It would be great to extend this with a small project that connects a frontend to the FastAPI backend....
---

---
---

You can write your personal notes here; they will not be parsed and are for your own reference.
