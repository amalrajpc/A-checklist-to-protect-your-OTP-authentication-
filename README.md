# A-checklist-to-protect-your-OTP-authentication-
I'm here to help pentesters by offering a concise checklist of items to help them verify the  OTP authentication.


Check whether the OTP is present in the bo response body.
Check whether the OTP is sent via URL parameter or not.
Check whether the server properly validate the received OTP. (Shared OTP == or != Received).
Check the randomness of OTP generation.
Check whether the OTP is leaked through response headers.
