Speaker 1 | 00:06
This SWFACE right? So that'll be the first task. The second is obviously we need to. Thanks Jason for confirming. Or that this is also a practice where even though the system is not implemented, still we would do the initial testing. 
You know, which is good to know about. So these are a couple of things I wanted to chat with the team and so I'll give the floor to you.
Speaker 2 | 00:48
So, I SDAR if you can just kind of what's the objective of phase one?
Speaker 3 | 00:50
Go ahead.
Speaker 1 | 00:51
Before respond.
Speaker 3 | 00:58
Actually.
Speaker 1 | 01:00
We, as you know, this is a IV and VEP program, right? And in. And so, Maximus, I'll give you a brief background. Maximus is the third party administrator for this child health care provider based in Florida. Okay? 
So with every government project, obviously it's a massive project for Maximus, and it's over about seven years or so, which is still extendable. So with every one of those projects, the government mandates that the provider has an independent verification validation of their systems, processes, et cetera. Because this is got not just systems, I mean systems relating to process of collecting premiums and all that. 
So it is. It's got a lot of th. 
So as part of that, we were selected to do this. IV NV this system is scheduled to go live, I think somewhere in 2025. Okay, so that's why I think a lot of these questions about the cart before the horse in terms of okay, the product is still not ready still, why are you asking us to test? 
So we have training which is going through the same thing. But then still there. 
So then we gave them a proposal. S sow starting from, I think October of 2023, going all the way to deployment. And so then they asked us to break it into two. 
So the first phase is, it's scheduled to end somewhere in March. What this first phase entails is, as I told you earlier, is we do the r rtm requirements management, traceability. 
So I've already completed the first round of it, and now I'm waiting to get the second round of itt, which will be subt next month. We already started, the hardware and software. For example, I think you already met Ken Brown. He's doing the a WS, you know, reviews. Then we have Andrew, who's doing the software development, best practice, code assessment and all that. I will actually send you the kickoff tack, which will walk you through all the different domains we're working on. 
So the key domains will be systems development, I mean software development, operations environment, which is SCAN, then requirements QA as you saw yesterday, which is a big blocker. I mean in terms of their understanding. Then we have security, obviously. 
So these are, I think, six or seven and project management. So there are six or seven domains which we have been contracted to do the, IV and do I answer your question or am I going wrong?
Speaker 2 | 04:40
So yeah, I'm familiar with the kickoff deck and the domains. We've been on quite a few calls so far. So when you say requirements management, traceability, are you just looking at the contract? Massing the contract to what exactly?
Speaker 1 | 04:56
So the contract is at a very high level, right? And then they actually created a Excel document which is supposed to bring it down, drill it down to the next level of requirement. 
And then. So. Which is done by Maximus. 
So the end of day they want to make sure that whatever is in the contract is solutioned by Maximus. And this workbook Excel workbook is a master workbook. And from there what happens is they will start creating BR DS, right? And the B R DS will be created. Then they will start solutioning it. They're using Agile, so they'll be doing it in different PIS and all that, right? The end of the day, making sure that the, information they feature a solution. Then you're able to trace it all the way to the testing documentation, right? 
So it goes all the way from. Because one of the things for Florida Healthcare is at any given point, they should be able to come into any of these workbooks and make sure that their requirement has been solutioned and they need to know what the what stage they are. Et cetera. 
So that is the rtm piece of it. So within the requirements we have these two pieces, one is the RTM the traceability of the requirement, and the second one is the security or sodn all that.
Speaker 2 | 06:37
Okay, so this Excel workbook that took the contract and that was created by Maximus, what is that called?
Speaker 1 | 06:46
It is called FHKRTM, actually.
Speaker 2 | 06:53
I'll share the F KC requirements traceability matrix.
Speaker 1 | 06:57
No, let me just give me a second. It's called, it's just called FHK space RTM workbook. I can share that with you after this call.
Speaker 2 | 07:18
That's fine, I'll find it. Thank you.
Speaker 1 | 07:20
Yeah, it's in the requirements. And one of the things we are doing is to let you know again, this. I've put together this spreadsheet for our own understanding. And this would be like the granular level. 
And then we and this will feed into the status deck, which we review every week. So this actually will walk you. 
So for example in the requirements rtm space I've created this where I saying I am doing the business AC requirement traceability from contract to this RT M workbook. Then I'm going through PRDR user story and test results. 
Right? Then I'm reviewing the p the PI whether the appropriate pii it has been solutioned in. 
And then I'm looking at this. Integrity is the increment plan. Increment for basically, yeah, okay, the traditional one used to be the waterfall. Now these guys are using what is called the Agile framework for development. 
So it's safe. Agile framework they're using for development, which is basically every two or it's called Sprint, which is about two or three weeks of sprint within which they will turn around a requirement into a feature, right? 
And then they'll demot. So rather than in the traditional way where used to have in buckets, right? 
So you'll have requirements gathering, then you'll have requirements analysis, then you'll have a design. So these were all one after the other. Sequence here what will happen is rather than doing that, they will say, Okay, I'm taking off this hundred, I'm taking fifteen to be featured and solution in this sprint, right? 
And then they'll go through an entire life cycle. DLC of the software is completed within that 15 days or two three weeks. 
So that's what it is.
Speaker 3 | 09:53
So this is essentially a quasi project plan. Just the steps. With the steps you're taking to complete your work. Is what it looks.
Speaker 1 | 10:03
No, this one I'm saying hey these are for example what other steps I am taking. You are right. And what other steps I am taking to do a traceability of the requirement? What are the key components? 
Right? The components are basically first as you have a T the contract administrator, right? The third party contract and I am mapping that to this workbook. 
Right? That is my first rae because if the requirement is not mapped that means I do not have the total population to be solutions. 
So I have a cap. So again this is more rtm. It's all about gaps, right? Then the second one is to say okay, the solute the requirements in the LTM workbook which PI or the it is being solutioned in so you know, okay of the 115 of them is getting done in the PI 1. Okay, so that means. Okay.
Speaker 3 | 11:03
I can we stop for one second because honestly, I know I understanding is we're coming in to do an ivnv of requirements. Yeah, this. 
I mean, what you're showing is all reviews of contracts requirements contained within a contract, which are fine. So I guess.
Speaker 1 | 11:23
I'm showing you what I've what I have done from the requirement standpoint. Okay, now what I am looking at to you is, hey, what are the four or five different tasks I'll be doing right? To deliver XYZ from the security standpoint in terms of, let's say, the design review, right? Making sure there's no gaps in whatever, right? That's what I'm looking at. I'm not. I'm just sharing what I've done in terms of my requirements analysis. 
Well.
Speaker 3 | 12:03
I understand. I understand and I appreciate we appreciate the sharing of information. It's just I'm sitting here and I'm literally I'm like, we're talking an IV AND V. That's typically an audit where we, you know, obviously we can't talk to the clients, so we need to do it through a documentation base. 
Yeah. And notes that are already received, which are going to be potentially suspect, because if nobody had a security lens, probably not going to have the information. I'm just being straight up forward, man, because honestly, we're burning a lot of psychos on this student. We have not gotten it. I'm not even got a meeting with a client. No, I'm.
Speaker 1 | 12:36
You know what I was they said and I'm like I understand and I will have.
Speaker 3 | 12:38
They said they were just been in cycles here over nothing. Yes, and not getting anywhere. No.
Speaker 1 | 12:47
Yeah, that's what like I made the request yesterday and now they have come back with that question. So I hopefully after this meeting, you know, if you can reply to that email and put all doubts away saying this is part of the process, then that will help us move forward with this right now.
Speaker 3 | 13:08
We can develop it. I can't put together a timeline for you until we actually know, you know, for me. 
So as I understand, I was told that there was. The other groups are basically doing a review of the SP and they held some interviews. Potentially, I'm not sure on that one, but then they provided feedback based on the SSP and the, the interviews they held, is that correct?
Speaker 1 | 13:34
Yeah, the yes.
Speaker 3 | 13:37
And they did no testing of any kind of.
Speaker 1 | 13:39
No. So no.
Speaker 3 | 13:41
So that I guess that was one of the initial things is we had the understanding that we were going to come in and actually do an evaluation and an assessment and testing. Based on our standard approach or a modified version of our standard approach, which always includes discussing things with the client and then looking at documentation as well as it pertains to the specific control as opposed to just doing it. 
I mean, I've done it before, and it's always federal government work. And that's why federal government security sucks, is because they just basically do things. Of a documentation. Review the SSP and tell me how my requirements matched up to what the compliance requirement is. I think it's a shitty way of doing an audit, but that's just personal preference. But if that's where they wanted to do it, then we should have been started two weeks ago. 
Yeah, I have not gotten any direction on. I've basically been handed a contract, handed a boatload of documentation, and I have nothing to go on in regards to direction. Conversations with the client and what the hell are we doing from a high level. Then we can dig in deeper on the details. But we're starting with the details, and there's no high level understanding where these are going to match back to.
Speaker 1 | 14:46
Let me ask you one question. Did you ever get a chance to talk to Luke or. Because not Kenn Luke.
Speaker 2 | 14:54
Yeah, we talked Bran.
Speaker 1 | 14:59
Luke yes, okay, did you get any insight from Luke?
Speaker 2 | 15:04
Loop that look at the contract, map the contract to controls, but they've essentially done that is what it looks like. I mean, they didn't put the control in here. But the controls are in the SSP. 
So the controls are already there.
Speaker 1 | 15:21
Okay, yeah, so, so I would. So now that you've put together this, controlled slide, right? 
So essentially what we're saying is going back and telling them, Hey, we did a sample, right? And these are the samples we'll be working on. 
So the first thing we are asking, to Jason's point, is the scope, right? And there's that's why they're coming back and saying, why are you asking me about the scope? Right. Because that's what we.
Speaker 3 | 15:57
That's if we. If we don't scope it, then there's. What are we assessing? 
I mean, I'm I mean, that's the first rule of an audit. What's the defined parameters, right? Yes.
Speaker 1 | 16:14
So what we again this is just a conversation here is we are going to say that hey, this is the scope we have taken on for this control the security assessment. Right? 
And then and this is going to be at the assessment at the design level, right? Obviously knowing that the product is not deployed, so which could be a second round. When the product is deployed, we might be doing a second round of security testing, but this is going to be the initial one where we are looking at your design, your road map and your policies, et cetera. Which you which you have set in the SSP document, right?
Speaker 3 | 17:07
And so then we're doing a documentation based documentation audit is what it sounds like.
Speaker 1 | 17:12
That's how I look at it. So that's what Jason, I would. I would appreciate if you can do is if you can reply to Brandon. But we' we're saying that, hey, as a first step, I we assume that there's going to be two rounds of testing. One will be at the design level where we are reviewing our policies, procedures, road map, et cetera. And the second one will be around once the product is deployed and these are the controls we'll be looking at. We're reviewing it as a sample. And so I think I would assume that's how it will go. At least you can get a confirmation from that saying, Okay, A.
Speaker 2 | 18:01
Okay, go. Sorry, I was gonna type it out. So the SSP includes controls, but it doesn't include security requirements, like at an organizational level. Sridar does that exist? Do you know.
Speaker 1 | 18:24
I would hate to say yes, because one thing is, they would say yes. It's all in the SSP document. But then it is each product might be following its own.
Speaker 2 | 18:44
Okay, let me ask this another way. So Maximus is the organization. 
Well, what's the organization?
Speaker 1 | 18:53
Maximus is the organization for which we are doing IV and B.
Speaker 2 | 18:57
Yeah, okay, so, let's use like the code development as an example. They were only doing a document assessment. Did whomever from the RSN team that was assessing their code process or the way they develop code, did they get like a, a secure coding requirement document or policy?
Speaker 1 | 19:23
So what they will be, I think what they will be getting or I'm not sure if they already got, which is Andrew is basically they would give them a standards, you know, what are the coding standards, right? And, so Andrew would take that coding standards. 
And then he will he's getting access into the code repository, so he will go in and do an assessment of the code to make sure that it is in alignment with the standards and then make this statement. Previous statement.
Speaker 2 | 19:59
Okay. So documentation like procedure policy and standard documentation. Yes, being requested. 
Yeah.
Speaker 1 | 20:07
So if you have anything specific in terms of security, right, I know you. The SSP is provided, but if you are looking for something else, if you need to bring it up with Brandon.
Speaker 2 | 20:20
Fair enough. I'll put a list together.
Speaker 3 | 20:23
We should just take the approach. We'll review the SSP, develop a list of questions. You can start your list of questions now, Devon. But maybe they'll be maybe something's going to be answered. The SSP because I know it's a pretty lengthy document actually.
Speaker 1 | 20:38
Yeah. INS just to let you know, Devin, the connection point is the chunk of it the bigger beast. And I think they have a lot of rigor and best practices. I would say around that, but doesn't mean that every other application or component as a used interchangeably follows the same suit. 
So you might find for example, I'll give you.
