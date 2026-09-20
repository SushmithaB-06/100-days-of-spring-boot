A Servlet is a Java class that receives HTTP requests and sends HTTP responses.

Think:

Browser
   ↓
HTTP Request
   ↓
Servlet
   ↓
Java logic
   ↓
HTTP Response
   ↓
Browser

For example, you enter:

http://localhost:8080/student

The browser sends:

GET /student

A servlet can receive that request.

Simple Servlet
@WebServlet("/student")
public class StudentServlet extends HttpServlet {

    protected void doGet(HttpServletRequest request,
                         HttpServletResponse response)
            throws IOException {

        response.getWriter().println("Hello Student");
    }
}

Now:

/student
     ↓
StudentServlet
     ↓
"Hello Student"
