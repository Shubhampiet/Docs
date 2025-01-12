**This is all about what happens behind when you request something from your browser.**

When you request something from your browser a bunch of JARGONS comes in the story but take this like a game of two players (browser and server) but this game contains lots of rules (protocols).

_User_agent or Client_
This is a medium that helps you to communicate with server.
Ex: Web Browsers, 
Apps
Web Crawlers: Automated bots like Googlebot, 

_Local machine_
This is your machine. It can be your laptop, PC , mobile etc.

_Server_
This is also a machine that fullfills your request. This is generally a heavy machine that is far away from you 

_HTTP-HyperText Transfer Protocol_
HyperText--> This is a text that can contain hyperlink(link of another document) that navigate you to another part of the same document or another document of the intenet.
Transfer----> This is simple movement of data/information.
Protocol----> This is fancy name of pre-defined rule.

_What is session ?_
A session is a time limit in which a browser and a website can communicate. It helps the website remember who you are and what you're doing while you're there.

When session expires or ends : 
A session will end when user log out, browser close or pre defined session time expires.

_Cookies_
What Are Cookies?
Cookies are small pieces of data stored on the user's device (browser or client-side) by a website to remember information about the user. They are used to make the web experience more personalized and efficient.

Session Cookies: It expires when a session ends.
Persistent Cookies: Remain on the user's device until they expire or are deleted

_What is Cache_
A cache is like a temporary storage box that saves frequently used data so that it can be accessed quickly later, without having to load it again from the original source.

Imagine you visit a library and read a book. Instead of going back to the shelf every time, you keep the book on your desk so you can grab it instantly. That’s what a cache does for your computer or phone.
Ex: Browser cache, App cache, server cache, phone cache.

Benifits of cache:
1. It saves time.
2. It saves resources.
3. Cost efficient

Downside of Cache:
1. Space consumption
2. Cache error
3. Outdated information

**Request - Response Model**
This is a simple model in which one(generally browser) requests for some information and other(generally browser) delivers information. 

**Ways to interact with server**
A browser can request to server through following methods

1. Get: When you want some data from browser. Analogy: Son: "Father please give me chocolate" 
2. Post: Used to create a new resource on the server. Ex: Posting something on instagram, twitter etc.
3. Patch: Used to partial update an existion resource: Ex: Edit your post on twitter
4. Put: Used to replace an existing resource. Ex: e.g., updating the tweet with new content, effectively replacing the old one
5. Delete: Used to delete existion resource. Ex: Delte an existion tweet.

A server responses to browser with specific data and status code.

_What is status code ?_
These are mathematical value that have pre defined meanings.

1. 200 OK
Meaning: The request was successful, and the server has returned the requested data.
Ex: "Hey son, take your chocolate."

2. 201 Created
Meaning: The request was successful, and a new resource was created.
Ex: "I’ve made you a new chocolate cake."

3. 400 Bad Request
Meaning: The request was malformed or invalid; the server could not understand it.
Ex: "Son, you’re asking for a chocolate that doesn't exist!"

4. 401 Unauthorized
Meaning: The user is not authorized to access the resource. Authentication is required.
Ex: "Sorry, son, but you need to ask your mom before you can have the chocolate."

5. 403 Forbidden
Meaning: The server understands the request, but it refuses to authorize it.
Ex: "Sorry, son, no chocolate for you today!"

6. 404 Not Found
Meaning: The requested resource could not be found on the server.
Ex: "Son, I can't find your chocolate!"

7. 500 Internal Server Error
Meaning: The server encountered an error and could not fulfill the request.
Ex: "Oops, son, I can’t give you the chocolate right now

8. 503 Service Unavailable
Meaning: The server is temporarily unavailable, usually due to maintenance or overload.
Ex: "Sorry, son, shop closed for maintenance—no chocolate for now!" 

**Evaluation of web**

_Web 1.0 (Static Web):_

The first version of the web.
Content was static and read-only (mostly text).
No interactivity or multimedia support.
Primarily used for sharing information, not for widespread public use initially.

_Web 2.0 (Dynamic and Social Web):_

Enabled dynamic, user-generated content and interactivity.
Supports multimedia (images, videos, audio, etc.).
Brought features like social networking, blogs, and e-commerce.
Focused on centralization, with platforms controlling user data.

_Web 3.0 (Decentralized Web):_

Focuses on decentralization using blockchain and peer-to-peer networks.
Aims to give users more control over their data.
Incorporates AI, machine learning, and semantic web concepts for a smarter internet.
Still evolving and not fully adopted.

