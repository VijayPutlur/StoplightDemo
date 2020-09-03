# Welcome!
</br>
<span style="font-size: 3em; color: #5D535E;">
  <i class="fas fa-robot fa-2x"></i> <i>Claims
</i></span> 
</br>
</br>

Interact with the `'Claims'` API to get a list of available claims, create or delete and to update existing claims.


</br>
<ul class="fa-ul" style="list-style-type:none;">
  <li><span class="fa-li"><i class="fas fa-check-square"></i></span>Creating claims</li>
  <li><span class="fa-li"><i class="fas fa-check-square"></i></span>Delete claims</li>
  <li><span class="fa-li"><i class="fas fa-spinner fa-pulse"></i></span>Load claims</li>
  <li><span class="fa-li"><i class="far fa-square"></i></span>Update your claims <strong>Claims<strong></li>
</ul>

### Code Generation

**Claims**'s API documentation provides code generation to get your project started as soon as you imagine it!

```javascript
var data = JSON.stringify({
  "claimId": 0,
  "type": "string",
  "status": "string",
  "policyId": "string",
  "ClaimInfo": {
    "id": 0,
    "submissionDate:": "2019-08-24",
    "gender": "FEMALE",
    "dob": "2019-08-24",
    "email": "user@example.com"
  }
});

var xhr = new XMLHttpRequest();
xhr.withCredentials = true;

xhr.addEventListener("readystatechange", function () {
  if (this.readyState === this.DONE) {
    console.log(this.responseText);
  }
});

xhr.open("POST", "https://medibankdemo.stoplight.io:5555/api/claims/create");

xhr.send(data);
```
> __*Claims*__ is one of the major key thing in our business and `API`s are just as great as our user-friendly UI, making us the first choice for systems integrators.

### Interactive Documentation

With the `'Try It!'` functionality you can send requests directly to our servers provided that you have a valid account and **Claims Key**, if you are not an existing customer you can use the built-in mock server for free! Click `'Send'` in the embedded _**Request Maker**_ below to get a sample mocked response:

```json http
{
  "method": "get",
  "url": "https://medibankdemo.stoplight.io/api/claim",
  "headers": {
    "Prefer": "code=200, example=PolicyDetails"
  }
}
```


