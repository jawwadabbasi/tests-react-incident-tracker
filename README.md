# React Frontend Test – Incident Tracker

Build a simple React app where users can submit incident reports and view recent logs. 

The form should include required fields like title, location, and severity (Low/Medium/High), along with optional fields like notes and name. 

On submit, post the data to https://jsonplaceholder.typicode.com/posts, display a success message, clear the form, and also save the data to localStorage. 

On app load, check localStorage for saved incidents; if none are found, fetch 5 sample logs from the same API and display them as a list of recent reports. 

Use React functional components with useState and useEffect. 
Avoid Redux and external libraries.

📄 [[PDF Version]](./react-frontend-test-incident-tracker.pdf)

---
**Test designed by [Jawwad Ahmed Abbasi](https://www.linkedin.com/in/jaabbasi/)**