# A-checklist-to-protect-your-OTP-authentication-
I'm here to help pentesters by offering a concise checklist of OTP authentication.


  Check whether the OTP is present in the response body.
  
  Check whether the OTP is sent via URL parameter or not.
  
  Check whether the server properly validate the received OTP. (Shared OTP == or != Received).
  
  Check the randomness of generated OTP.
  
  Check whether the OTP is leaked through response headers.

  Check whether same OTP can be used multiple times.
