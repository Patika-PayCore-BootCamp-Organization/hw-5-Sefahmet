
**1** – What are Authentication and Authorization 

Authentication is verifying system. For example, if you want to log in to system, the password is authentication.

Authorization is setting to usable things. For example, when you want to edit the profile setting in your Facebook account, your authority is limited. You cannot change the time to start using Facebook but you can change your personal information. 

**2** - What is Hashing in Spring Security?

In order to send a message to a place secretly, instead of sending that message directly, an encryption process is done by creating random strings and storing their correspondence. This process is called hashing.

The basic features of Hashes are:

Deterministic, same message equals to same hash every time.

Reversible, the message should not obtain from the hash.

High entropy, a small change on hash to cause the big change on messages.

Collision, two different messages cannot represent by same hash.


**3** - What is Salting and why do we use the process of Salting?

Salt means random hash. It causes the high entropy, and it cover against the pre-compiled hash tables (rainbow tables). For example, if we have easy level password (12345678), it must be in the hacker password list and it will try firstly. But if we have random 8 bit string, probably it will not in the pre-compiled list.

**4** - What is “intercept-url” pattern?

\-

**5** - What do you mean by session management in Spring Security?

Session management does;

Session Timeout detection and handling, Concurrent sessions (how many sessions an authenticated user may have open concurrently), Session-fixation – handle the session.

**6** – Why we need Exception Handling?

The process of writing an error-free code is almost impossible, we may encounter errors inevitably, and by catching these errors with the use of Java Exception Handling, we can learn from where and why our problem originates.


**7** - Explain what is Authentication Manager in Spring security?

AuthenticationManager is the interface that returns the result of the login process. The result of this action is True, AuthenticationException, or Null.

**8** - What is Spring Security Filter Chain?

The filter can enable us to check the request and response or make changes if necessary before the HTTP request made by the user comes to the application codes we have written. As a general usage, it can be used to direct the request to other pages or to print a log for each incoming request, whether it meets the conditions we have determined.

FilterChain contains the algorithm that allows us to group the filters and run them in order. The applied pattern name is called a chain.

**9** – What are the differences between OAuth2 and JWT?

Firstly, we have to differentiate JWT and OAuth. Basically, JWT is a token format. OAuth is a standardized authorization protocol that can use JWT as a token. OAuth uses server-side and client-side storage. If we want to do real logout, we must go with OAuth2. Authentication with JWT token cannot log out actually. Because we don’t have an Authentication Server that keeps track of tokens. 

**10** - What is method security and why do we need it?

Backend and frontend are disconnected in a properly designed app. The backend security system cannot assume that any particular frontend will handle security properly, so it has to handle it itself.

**11** – What Proxy means and how and where can be used?

When we enter a site, our IP address is monitored by the site. To prevent this, we transmit our request using an intermediate server (Proxy). Our request actually goes to the proxy server and from there to the site, so the site sees the proxy's IP, not ours. It can be thought of as a digital version of the game auricularly.

**12** – What is Wrapper Class and where can be used?

Wrapper Class is converts the primitive objects to class. Java is an OOP language and it want each objects in class. For example, “1” it can be string or Integer, so we must defined as Integer or String.

**13** – What is SSL? What is TLS? What is the difference? How can we use them?

SSL is a cryptographic protocol that uses explicit connections to establish secure communication between web server and client.

TLS is also a cryptographic protocol that provides secure communication between web server and client via implicit connections. It’s the successor of SSL protocol.

Both are X.509 digital certificates that help authenticate the server and facilitate the handshake process to establish a secure connection.

When comparing SSL vs TLS, the SSL and TLS protocols are different in their functions, authentication of messages, alert messages, record protocol, and encryption strengths. TLS is the successor of SSL.

**14** - Why do you need the intercept-url?

\-
