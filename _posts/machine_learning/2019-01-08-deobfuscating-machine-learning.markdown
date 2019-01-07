---
layout: post
title:  "Deobfuscating Machine Learning"
date:   2019-01-08 01:18:41 +0530
categories: Machine Learning
permalink : "/ml-for-all/"
---
# De-obfuscating Machine Learning

> One word is too often profaned 
> For me to profane it.
> One feeling too falsely disdain’d,
> For thee to disdain it. 
	>    -- <cite>P.B Shelly</cite>
														
With technology comes more power and with more power comes responsibility. Every technology comes with it's own subtle terms and conditions and the major one being using it with utmost responsibility. 

Today, unfortunately the knowledge one has about a technology has become synonymous with the *__jargons__* one can remember and use. The more obfuscation you create, the more knowledgeable you are. It is only unfortunate that we have are institutionalised to such social conditionings. 

I think jargons are by no means the measure of knowledge. The purpose of knowledge is not to prove the possession of it rather the implementation. I think it is only apt to quote Miles Kington here :
>  Knowledge is knowing that a tomato is a fruit, wisdom is not putting it in a fruit salad.
>  --<cite> Miles Kington <cite>

The purpose of education should be to create enablers and not subscribers who subscribe to convenience of using jargons. I see excessive use of jargons as an attempt to make the knowledge proprietary and monetize it. 

I am not attempting to frame the act of monetizing the knowledge as long as it is not intended to create knowledge parasites out of the learners.  I am starting a series of articles where I will be taking on the mission of de-obfuscating the Machine Learning jargons and give away a very simple explanation of those terms. 

eg: 
1. Linear Separability :
![Traffic](https://rdcnewscdn.realtor.com/wp-content/uploads/2018/01/LA-traffic-jam.jpg) 

Can you draw a straight line anywhere on the above picture such that it separates the vehicles going in either directions ?
The answer is a simple Yes. Just draw a straight line on road divider  (in most cases where traffic rules are followed) . Hence we say that the vehicles going in either directions are linearly separable.
Mathematically , Let ![X_{0}](http://bin.sensegates.com/s/9/e/1/9e18f94ce7b1bda0a4742a1fd4437581.png) and ![X_{1}](http://bin.sensegates.com/s/5/f/5/5f5bcbe5a5e9accc4ea20a6ef79d196d.png) be two sets of points in an n-dimensional space. Then ![X_{0}](http://bin.sensegates.com/s/9/e/1/9e18f94ce7b1bda0a4742a1fd4437581.png) and ![X_{1}](http://bin.sensegates.com/s/5/f/5/5f5bcbe5a5e9accc4ea20a6ef79d196d.png) are linearly separable if there exists n+1 real numbers ![w_{1}, w_{2},..,w_{n+1}](http://bin.sensegates.com/s/c/0/e/c0e25b8de3fa94adf05d5c879e89ec30.png), such that every point ![x \in X_{0}](http://bin.sensegates.com/s/b/b/e/bbe1a02df9fc417afc789df67e8f1e4b.png) satisfies ![\sum^{n}_{i=1} w_{i}x_{i}\ge w_{n+1}](http://bin.sensegates.com/s/e/6/7/e6745dadeb87bae8b149b6a66bd6cb1e.png) and every point ![x \in X_{1}](http://bin.sensegates.com/s/2/1/4/2141fb86544d6e3da389719546b52b19.png) satisfies ![\sum^{n}_{i=1} w_{i}x_{i} < w_{n+1}](http://bin.sensegates.com/s/6/b/4/6b47466dcbac320a2247b44b4aa9c585.png), where ![x_{i}](http://bin.sensegates.com/s/6/4/b/64b94619c0031522d16b05a37bc06189.png) is the i:th component of ![x](http://bin.sensegates.com/s/9/d/d/9dd4e461268c8034f5c8564e155c67a6.png)

### To be Continued ...