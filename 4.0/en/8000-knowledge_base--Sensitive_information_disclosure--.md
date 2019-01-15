## Description:

In applications it's common that information is sometimes used in the URL GET parameter but this brings possible sensitive disclosure to the attacker or on the system.
For example when the session cookie is used in the GET this can be reflected in the logs as well or in the Referer header. When the users then goes to a third-party website this session cookie will be exposed there. The third party can use this session cookie to take over the account of the victem.

## Solution:

Never use sentivie information in GET requests or cookies. 
