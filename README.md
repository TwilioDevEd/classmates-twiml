[![Learn to code with TwilioQuest](https://img.shields.io/static/v1?label=TwilioQuest&message=Learn%20to%20code%21&color=F22F46&labelColor=1f243c&style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIAAAACACAMAAAD04JH5AAAASFBMVEUAAAAZGRkcHBwjIyMoKCgAAABgYGBoaGiAgICMjIyzs7PJycnMzMzNzc3UoBfd3d3m5ubqrhfrMEDu7u739/f4vSb/3AD///9tbdyEAAAABXRSTlMAAAAAAMJrBrEAAAKoSURBVHgB7ZrRcuI6EESdyxXGYoNFvMD//+l2bSszRgyUYpFAsXOeiJGmj4NkuWx1Qeh+Ekl9DgEXOBwOx+Px5xyQhDykfgq4wG63MxxaR4ddIkg6Ul3g84vCIcjPBA5gmUMeXESrlukuoK33+33uID8TWeLAdOWsKpJYzwVMB7bOzYSGOciyUlXSn0/ABXTosJ1M1SbypZ4O4MbZuIDMU02PMbauhhHMHXbmebmALIiEbbbbbUrpF1gwE9kFfRNAJaP+FQEXCCTGyJ4ngDrjOFo3jEL5JdqjF/pueR4cCeCGgAtwmuRS6gDwaRiGvu+DMFwSBLTE3+jF8JyuV1okPZ+AC4hDFhCHyHQjdjPHUKFDlHSJkHQXMB3KpSwXNGJPcwwTdZiXlRN0gSp0zpWxNtM0beYE0nRH6QIbO7rawwXaBYz0j78gxjokDuv12gVeUuBD0MDi0OQCLvDaAho4juP1Q/jkAncXqIcCfd+7gAu4QLMACCLxpRsSuQh0igu0C9Svhi7weAGZg50L3IE3cai4IfkNZAC8dfdhsUD3CgKBVC9JE5ABAFzg4QL/taYPAAWrHdYcgfLaIgAXWJ7OV38n1LEF8tt2TH29E+QAoDoO5Ve/LtCQDmKM9kPbvCEBApK+IXzbcSJ0cIGF6e8gpcRhUDogWZ8JnaWjPXc/fNnBBUKRngiHgTUSivSzDRDgHZQOLvBQgf8rRt+VdBUUhwkU6VpJ+xcOwQUqZr+mR0kvBUgv6cB4+37hQAkXqE8PwGisGhJtN4xAHMzrsgvI7rccXqSvKh6jltGlrOHA3Xk1At3LC4QiPdX9/0ndHpGVvTjR4bZA1ypAKgVcwE5vx74ulwIugDt8e/X7JgfkucBMIAr26ndnB4UCLnDOqvteQsHlgX9N4A+c4cW3DXSPbwAAAABJRU5ErkJggg==)](https://twilio.com/quest?utm_source=gh-badge&utm_medium=referral&utm_campaign=classmates)

# Get your classmates all together on the phone

After completing this course, you will have built a working phone application that will connect callers to a conference call.

You can use this to connect with friends you've been missing! ☎️

<!-- Video goes here -->

We're so glad you're spending some of your time learning to code, and we can't wait to see what you build!

[@craigsdennis](https://twitter.com/craigsdennis)

[Teaching Guide for teachers](teaching-guide.md)

## Sign up for Twilio

Sign up for your free trial with Twilio. If you use this link with promo code to sign up, you'll get double the 💰 Free Trial credit. You deserve it.

[https://www.twilio.com/promo/classmates](https://www.twilio.com/promo/classmates)

## The code

This is the `TwiML` (Twilio Markup Language) that you need. You can host this using a [TwiML Bin](https://www.twilio.com/console/twiml-bins) and wire it up to your [phone number](https://www.twilio.com/console/phone-numbers/incoming) for incoming calls.

### Say Anything

```xml
<Response>
    <Say>You can have your call say anything you want it to by using the Say tag</Say>
</Response>
```

### Dial a Conference

The `<Dial>` tag allows you to dial numbers as well as a [Voice Conference](https://www.twilio.com/docs/voice/conference). If you put a conference name in there that doesn't yet exist, or is no longer active, it will create a brand new conference for you.

```xml
<Response>
    <Say>Connecting with your classmates</Say>
    <Dial>
        <Conference>Classmates</Conference>
    </Dial>
</Response>
```

## Learn more

There are a whole bunch of [TwiML verbs](https://www.twilio.com/docs/voice/twiml) you can use to build even more applications.

I recommend you check out the visual flow builder [Twilio Studio](https://twilio.com/studio).

Did you know that Twilio provides an actual video game 🎮 to learn how to code? Check out [TwilioQuest](https://twilio.com/quest?utm_source=gh&utm_medium=referral&utm_campaign=classmates) and help save the cloud.

If you'd like to run this with a group of kiddos, we've put together a [Teaching Guide for teachers](teaching-guide.md). Let us know how it goes!