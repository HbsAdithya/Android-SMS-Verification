# Android-SMS-Verification
# How It Works

  1. First user mobile number will be sent to our server where new user row will be created.

  2. Our server requests the SMS gateway for an sms to the mobile number with a verification code.

  3. SMS gateway sends an SMS to the user device with the verification code.

  4. The verification code will be sent back our server again for verification. Our server verifies it and activates the user.
