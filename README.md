A Simple WAF Based on Caddy Server.


# Decision Center
This module is charge for the decision, will do action for each request.
The action is in "allow", "block", and "watch".

Allow: No effect in user side except add a repsone header.
Block: Will block the request and return http response with 5xx code.
Watch: Just for internal audit check,  for attack analysis.
# ipip.net
https://github.com/ipipdotnet/ipdb-go
