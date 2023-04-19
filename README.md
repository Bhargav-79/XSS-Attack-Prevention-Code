# XSS
Injecting a script on any input tags is rough idea of what XSS is.

# Approach
To prevent XSS I have used htmlspecialchars() function in order to encode the input or sanitize the data.

# XSS Attack Prevention Techniques
1. User Input escaping
2. We should consider all Inputs as threat
3. Data Validation
4. Sanitizing the data
5. Encode the output
6. Using right response headers
7. Using content security policy