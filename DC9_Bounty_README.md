# DC9's Guide to ETHDenver 2023 Bounty Payments  

Congradulations to all the winners!  I put this together to help navigate the claim process.  

**NOTICE: This is NOT an official guide.**  
If you have any questions you'll want to use ETHDenver's Discord/Articles and OpenQ's documentation, but I am sharing my experience in case it is helpful for you.
UPDATE: OpenQ has released a [video on the claim process](https://www.youtube.com/watch?v=u93pTyhW9SY)

This repository is a fork of the official repo with 3 additional files in the root of the repo:
1. The .md file you are currently reading
2. A [template](https://raw.githubusercontent.com/denvercitizen9/ETHDenver-2023/main/PROJECT_NAME_YOUR_NAME.md) that you can use for your bounty payment submission
3. My actual bounty payment submission, which you can ignore

Check out these links for more info:

* **ETHDenver Bounty Article** (source for this info as of March 26th 2023)  
	https://ethereumdenver.medium.com/ethdenver-2023-track-and-bounty-winners-1d9cbeda1dc8  
* **Official ETHDenver/SporkDAO Discord**  
	https://discord.gg/sporkdao  
* **SporkDAOOfficial GitHub** (where you need to go to submitBounty Issues)    
	https://github.com/SporkDAOOfficial/ETHDenver-2023/issues?q=is%3Aissue+is%3Aopen  
* **OpenQ Claim Docs** (describe this bounty claim process)  
	https://docs.openq.dev/hackathon-winner/project-submission/pull-request-your-project-submission  
* **OpenQ Discord** (for any related issues)
	https://discord.gg/puQVqEvVXn  

#### WTF is OpenQ?
A hackathon payment platform for distributing pre-paid bounties.  In order to use it you will need to interact with multiple 3rd party systems and make a commit on GitHub.  Note that:
 - All ETHDenver Track Prizes will be paid through OpenQ
 - Most Sponsor Bounty Prizes will be paid by ETHDenver through OpenQ
 - Some Sponsor Bounty Prizes will be paid by the Sponsors directly (and you will need to work with them directly)
Note that ETHDenver is providing sponsor-specific updates at the end of the [ETHDenver Bounty Article](https://ethereumdenver.medium.com/ethdenver-2023-track-and-bounty-winners-1d9cbeda1dc8) so you can check that to see the status of your bounty.

# HOW TO GET PAID

### Step 1: Identify the GitHub Issue # for your Winning Bounties
The first thing you'll want to do is [search for your bounty and identify the issue number for your bounty](https://github.com/SporkDAOOfficial/ETHDenver-2023/issues).  

For example, my team won third place for [Best Use of Existing Subgraph](https://github.com/SporkDAOOfficial/ETHDenver-2023/issues/17).  You will need to find the correct issue # for each of the bounties that you won.  Remember the issue number(s) for each bounty that you won, you will need them for Step 4.  You will also need to remember the bounty name(s) for step 7.  

### Step 2: Create Your Submission File

You can create this file in your own repo after Forking the SporkDAOOfficial GitHub, or you can follow [OpenQ's official docs] and use the UI to do the same thing.  

I've incldued a [template](https://raw.githubusercontent.com/denvercitizen9/ETHDenver-2023/main/PROJECT_NAME_YOUR_NAME.md) that you can use as a starting point.  Note that you'll need your own new branch, because you won't be able to create a PR for main.  I chose violence and named my branch 'therearesomanystepstoclaimabounty'

However you create the file, you'll see that the file contains a list of self-explanatory comments; fill out your info and save the file.  You will need to change the file name.  In my case, **PROJECT_NAME_YOUR_NAME.md** became **JankaScore_denvercitizen9.md** - this is the only file that you need for submission.

### Step 3: Create a Pull Request for Your File

Once you've created a fork you can [go here to start a merge request](https://github.com/SporkDAOOfficial/ETHDenver-2023/compare/main...SporkDAOOfficial:ETHDenver-2023:main) and select 'compare across forks' to identify your fork (on the right side of the comparison) and submit your PR.  Your branch should only contain the file that you created in the previous step.

### Step 4: Link Your Pull Request to the Bounties You Won
After your Pull request is submitted you need to add a comment to your PR.  

Once you have your issue # (or #'s, you BAMF) you'll be able to follow the process on the [OpenQ Docs](https://docs.openq.dev/hackathon-winner/project-submission/pull-request-your-project-submission#link-your-pull-request-to-the-bounties-you-won) to add the comment to your PR.  Although some of you may know GitHub will recognize such comments in the comment of the commit for the PR, I woulds still recommend following the instructions to avoid any reasons for delays.

### Step 5: Associate a Wallet with GitHub
Follow the steps on the [OpenQ Claim Guide](https://docs.openq.dev/hackathon-winner/preparing-to-claim/associate-wallet-with-github).   
  
The short version is you go to the OpenQ website, connect with your GitHub, and connect your wallet.  

Wallet support is extremely limited (even less so than the project we submitted to the hackathon).  I wasn't able to connect my wallet after trying multiple wallets/browsers/devices.  Eventually OpenQ support suggested that I use Metamask with Firefox, which required me to enable the deprecated U2F JavaScript API that has recently been disabled by default in Firefox.  OpenQ suggested that Chrome was also working for people, but I didn't want to go through the trouble of setting up Metamask in another browser there just for this purpose.  

### Step 6: KYC  
Follow the steps on the [OpenQ Claim Guide](https://docs.openq.dev/hackathon-winner/preparing-to-claim/kyc-know-your-customer)  

Going through the KYC process wasn't too painful but also wasn't straightforward.  

Following the instructions I ended up with a third party "VeriLabs" which I don't know anything about.  I'm not sure who I gave what, but at the end of the day I needed to share my email, click a magic link, and "By continuing, I acknowledge that Persona analyzes my facial biometrics for the purposes of identity verification and immediately deletes the biometric data after processing."  

I'm not sure who Persona is, but as far as I know, my biometrics data is not on file with the State of Colorado or the United States government, and if it were, I don't know why it would be available for verification through Persona.  In any case, this is the only path to success so here we are.  

It took multiple attempts to verify, including different cameras/lighting.  This was very frustrating because there was not an option to request support or assitance and no feedback as to what was wrong with my verification.  In any case, it did eventually work and I was allowed to mint a KYC pass.  They kindly offered this for free (instead of the $5 that I assume I will have to pay for next year's renewal) but I didn't have MATIC in my wallet so I had to step away to go through that whole process.  

Lukcily I was part of a workshop last year that provided a few cents worth of MATIC, so I was able to send myself the $0.06 cents worth of MATIC that was necessary to complete the mint.  I also had to enable Blind Signing, which is a practice that I think needs to go away.  It makes sense as a pre-production development hack, but providing a user with meaningful transaction information needs to be an industry standard.  This is especially true after asking me to share my biometrics and PII.  

### Step 7: Upload W8/W9 form 
Follow the steps on the [OpenQ Claim Guide](https://docs.openq.dev/hackathon-winner/preparing-to-claim/upload-w8-w9-form)  

Providing some additional clarification that's not obvious in the docs.   

You'll need to navivate to [the hackathon on OpenQ's website](https://openq.dev/repo/SporkDAOOfficial/ETHDenver-2023) and find your bounty there.  The issue # that you entered originally won't work, so you'll have to search by name of the bounty.  I used what I thought was a unique word in the title of the bounty.  From there you can: 
 * Click on your bounty  
 * Click "Full Contract"  
 * Navigate to "Claim" tab  
 * Click button "Choose PDF File" and upload your w8/w9    
 
You will see a couple of additional messages:  
"We have sent your tax document to the organization [ETHDenver]. Please wait until they have viewed and confirmed them. If they request changes, you will be notified via your contact email. If you have any questions, feel free to reach out in our Discord."   
and  
"Thank you for submitting your tax form. Kindly note that OpenQ is not involved in the reviewing process, which may take up to 19 days. We appreciate your patience and will notify you as soon as the process is complete."  

ETHDenver needs to approve your tax documents before you can claim your bounty.  According to recent emails the deadline for the approval to be complted is 5pm Mountain Time on June 19th, but the approval won't be sent to OpenQ for claiming until June 28th-30th.  This means you won't be notified before the deadline, even if the approval was successful.  I'm not sure what the process is if you are denied.  

If the approvals are not complete in time then you may not find out until after the deadline has passed.  If you have submitted all of your documentation but haven't received a response from ETHDenver, I would recommend contacting them by email to ensure that the approvals are complete.  
	
### Step 8 Claim Your Bounty  
Follow the steps on the [OpenQ Claim Guide](https://docs.openq.dev/hackathon-winner/claim-your-prize-amount)

I think after all of this I will be able to claim, but I can't claim yet because I'm still waiting on ETHDenver to approve my w8/w9 form in OpenQ.  I'll update again if I find out there are any additional steps.  
