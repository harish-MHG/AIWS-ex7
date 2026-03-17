# Node.js Basics – Lab Exercises

**Author:** HARISH GOKUL

---

## Exercise 1: Hello from Your Node.js Server

A simple HTTP server that displays a greeting message with the current date and time.

### Run
```
node server.js
```

### Test
Open your browser and go to:
```
http://localhost:3000
```

**Expected Output:**
```
Hello from HARISH GOKUL's Node.js Server
Current Date and Time: <live date and time>
```

### Network Testing
To test from another computer on the same network:
1. Run `ipconfig` (Windows) to find your IP address.
2. On the other computer, open:
```
http://<your-ip-address>:3000
```

---

## Exercise 2: Handling Multiple Routes

An HTTP server that responds with different content based on the URL.

### Run
```
node routeserver.js
```

### Routes

| URL | Response |
|-----|----------|
| `http://localhost:3000/` | Hello from HARISH GOKUL's Node.js Server |
| `http://localhost:3000/about` | About Page – This server is created using Node.js |
| `http://localhost:3000/contact` | Contact Page – Email: yourname@example.com |
| Any other URL | 404 - Page Not Found |

---

## Requirements

- [Node.js](https://nodejs.org/) v12 or higher
- No external packages needed (uses built-in `http` module)
