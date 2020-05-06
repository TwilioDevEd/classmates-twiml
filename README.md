# Get your classmates all together on the phone

After completing this course, you will have built a working phone application that will connect callers to a conference call.

You can use this to connect with friends you've been missing! ☎️

<!-- Video goes here -->

We're so glad you're spending some of your time learning to code, and we can't wait to see what you build!

[@craigsdennis](https://twitter.com/craigsdennis)

## Sign up for Twilio

Sign up for your free trial with Twilio. If you use this link with promo code to sign up, you'll get an extra **$15** 💰in Trial credit. You deserve it.

[https://www.twilio.com/try-twilio?promo=CLASSMATES](https://www.twilio.com/try-twilio?promo=CLASSMATES)

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

Did you know that Twilio provides an actual video game 🎮 to learn how to code? Check out [TwilioQuest](https://twilio.com/quest) and help save the cloud.
