# daily-question-javascript-q118
JavaScript Question of the day

You have the following form:
```
<form method="post">
         <div>
                <label for="first">First Name:</label>
                <input type="text" id="first" name="firstName">
         </div>
         <div>
                <label for="Id">Last Name:</label>
                <input type="text" id="last" name="lastName">
         </div>
         <div>
                <input type="submit" value="Submit">
         </div>
</form>
```
A user fills out the form and submits it.
------------------------------------------------

What will the request body contain?

A.<br/>
```POST http://localhost:35132/Account/FormTest HTTP/1.1<br/>
Accept-Language: en-US <br/>
Content-Type: multipart-data-JSON-node-js <br/>
Content-Length: 27 <br/>
Host: localhost:35132 <br/>

firstName=John&amp;lastName=Doe <br/>
```
B. <br/>
Nothing, the body of the message will be empty

C. <br/>
```
http://localhost:35132/Account/FormTest/firstName/John/lastName/Doe
```
D.<br/>
```
POST http://localhost:35132/Account/FormTest HTTP/1.1<br/>
Accept-Language: en-US<br/>
Content-Type: application/x-www-form-urlencoded<br/>
Content-Length: 27<br/>
Host: localhost:35132<br/>

firstName=John&amp;lastName=Doe<br/>
```
------------------------------------------------
Place your answer HERE -> 
