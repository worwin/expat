# expat

## Gmail Accounts Needed

### [New Gmail Account]

>For temporary porting, you will set this up, will likely need a non-voip number to setup at first. Do this with your telephone number before attempting to port it. This will not tie that number to this accounts google voice, only for 2FA.


### [Original Gmail Account]

>This is the account that you already use on your phone, for gmail, banking, and whatever else. This is where you will port your 806 number to. 

### Steps 1 - 3
>Steps 1, 2, and 3 are optional. This will help ensure that you have your accounts backed up to some number incase something with the porting goes wrong while you are relocating. I'm not sure how long a port will take.

#### 1. Create a [New Gmail Account]

>Navigate to: https://accounts.google.com/signin. 

>If you already have a GMail account, you will have to select your logo at the top right. This should drop down a menu with the option "Add Another Account" and from here you should be able to select "Create Account". If these navigation steps don't work, then Google has likely changed something up and you will need to figure out how to create a GMail account on your own.

>When doing this, Google will likely ask you to give them a cell phone number. This number will need to be your original number. This will not register your number with Google Voice. It will only set it as the 2FA (Two-Factor Authentication) method for your new account. Google doesn't allow Google Voice numbers for this, so it is best to set this account up before attempting to port your number to your [Original Gmail Account]. 

#### 2. Setup Google Voice with your [New Gmail Account]

>Once your account is created, go to https://voice.google.com. There should be a gear icon at the top right, or some way for you to navigate to a settings page. This may load by default if no number has ever been setup. 

>For me, this is the page https://voice.google.com/u/0/settings. You may be able to go directly here. 

>Once here, you can create a new google voice number. Select a random one. Don't port here. 

#### 3. Register Accounts with [New Gmail Account]
>From this point, you can now register any accounts you might have with this Google Voice number. For me, this only works with some Credit Cards, some less modern banks, and social media accounts. 

>It doesn't work with Wells Fargo, WhatsApp, and Bank of America.

#### 4. Port Over Original Number
> 1. Switch back to your [Original Gmail Account].<br>
> 2. Find where it says "Port a number" and begin the process. Not sure what this entails. Best of luck.

#### 5. Porting Completed
> Move any account setup with [New Gmail Account]'s google voice number to [Original Google Voice]'s number.
> Banks and Accounts that were left with your original phone number because they couldn't be switched to a voip number should now work with your [Original Google Voice]'s ported number.

#### 6. Google Voice
> There is a google voice app you can setup on your phone.
> Research how to setup wifi calling.
> When placing calls internationaly with Google Voice do so from wifi with airplane mode enabled OR risk encuring international roaming fees. 
> If for some reason calls can't be placed from wifi, look at setting up a VPN to place calls as if you were in the US. 

#### 7. VPN (For a Later Date)

#### 8. Telecom Basics
>ISD NPA  NXX BLOCK<br>
>+1 (575) 100 5001

>ISD (International Subscriber Dialing) [international code]<br>
>NPA (Number Planning Area) [Area Code]<br>
>NXX (Exchange code) <br>
>BLOCK (Line Number) [Subscriber Number]<br>

>https://localcallingguide.com/

#### 9. Explanation
>Likely, banks are using services like twilio to check if a number is a voip number or if it is assigned to a carrier. Since, the accounts were first setup with a number that was owned by a carrier (like ATT or Verizon), the Bank thinks they are not VoIp numbers. However, I would imagine they do audits every so often. Here they may go through each number and check it. If this is the case, then they may eventually catch that the number is now owned by Google Voice and not your original provider. In that event, the number will no longer work for 2FA. Worse, you won't know that it stopped working until you try and use the 2FA during a wire transfer or new login attempt. 