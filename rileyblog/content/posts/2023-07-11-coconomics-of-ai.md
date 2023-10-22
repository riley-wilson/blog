---
date: '2023-07-11'
title: Concussed economics of generative AI
---

> I think this general question of what's the market structure of value creation and capture in this AI landscape is kind of the big question
>
>-Nat Friedman

> Indeed, what I have written here makes no claim to novelty in points of detail
>
>-L.W.

Imagine you're vacationing in the Philippines. Lounging underneath a palm tree, you marvel at the beautiful country. There are gorgeous beaches, friendly people, and enough coconuts, you think, to supply the world. Everywhere you go, you see coconuts. They're sold in roadside stalls, carved into souvenirs, and featured in nearly every dish. In fact, coconuts are so abundant they're strewn everywhere around you... 

Above, a light tropical breeze rustles through the palm and massages a coconut from its home. The fruit makes haste for the ground but meets your head instead. You've been concussed by a falling coconut, but count yourself lucky. Only your technical knowledge — and proprioception — are impaired. Economic knowledge and common sense remain intact. You can't remember what a "transformer" is, describe a neural net, or walk in a straight line, but Econ 101 is untouched. 

Thank goodness, because now you get a call. It's your VC. She's running SPVs in generative AI companies and wants to know if you're in.[^2] Suddenly, you need a view on the industry. It's here, on wobbly, white warm sand you embark on a so-called "coconomic" analysis of AI. By nightfall, you must decide which kinds of AI companies are worthy of investment, else potentially miss out on the deals of a lifetime. 

-- 

Benighted, you begin with basics. What does generative AI do? Before, you may have answered it "predicted the next token." Now, you don't know what a token is. Best to start with an elementary understanding and work our way up. Text models, you think, make clever words. Image models make pretty pictures. These thoughts are not profound, but they're a start. Making these words and pictures is also absurdly cheap, you remember. In fact, generating a paragraph or a photorealistic image is almost so cheap to be free. Yes, you recall, the models themselves aren't cheap to build — GPT-4 cost more than $100 million to train — but the cost of teasing out words and images from a constructed model is low, and will get cheaper. In other words, AI makes the marginal costs of image and text manipulation approach zero.[^0] The insight hits you with the force of a second coconut. The internet age gifted us an abundance of information, and the AI age bears an abundance of custom text and images, but for a steep cover. 

Under this realization, you consider how the creators of generative AI will fare from a business perspective. Research labs-cum-companies like OpenAI, Anthropic, and Stability.ai are responsible for the most powerful models thus far. GPT-4 can pass high school physics, the bar, and do math. Challenger models (some of them open source) are hot on its tail. Google DeepMind blusters it has an even more powerful model, but has yet to release it. In the process, these labs made advances in computer science and collected thousands of citations. Impressive. 

However, the labs may be the worst businesses. If they choose to primarily sell text or the manipulation of text, that's a mistake. Given the marginal cost of text creation/manipulation is approaching zero, their profits on this product will be competed away. Would you sell a product whose price is always declining? Say OpenAI is selling GPT-4 access for 12 cents/1k tokens (what's a token again?). A competitor could just as easily undercut them and offer their comparable model (Bard, Claude, etc...) for 10 cents a token. Repeat the reasoning, and a plausible equilibrium is companies selling model access at cost. 

In theory, you reason, a research lab could build a defensible business by differentiating their product. Creating specialized models for narrow uses limits competition. Not all competitors will follow a company into smaller markets. Specialized models may also be a clearly superior product. Some AI companies are already on this tack. Cohere is making LLMs for ecommerce,  and ContextualAI is creating reliable LLMs for use with enterprise data. Mistral AI is somewhat mysterious, but I've read they have a strong emphasis on enterprise, rather than consumer, products. Companies with less direction include Stability.ai, which does not have a clear business model beyond selling API calls and making noises about "consulting" with enterprise customers. 

It's also possible to parlay general research success into a defensible business. Citations aren't directly monetizable, but attention is.[^4] A strong brand can secure distribution for more lucrative endeavors. For instance, OpenAI recently announced a marketplace for developers to sell AI apps built with their models. I think this is an excellent move. A marketplace differentiates OpenAI's models from the distribution side. Developers might be indifferent between GPT-4, Claude, Chinchilla, etc... from a performance perspective, but GPT-4 and other OpenAI models come with additional customer exposure via their marketplace, which gives them a reason to use their product. The key for OpenAI is to create a lively marketplace developers are excited to sell in. 

Unfortunately, creating lively marketplaces is hard. You need a critical mass of participants, and among them, an ideal split between buyers and sellers. Fortunately, OpenAI's research publicity softens both problems. In popular imagination, they're the industry leader in AI. Their marketplace, then, will be the first stop for customers seeking AI products. Developers will anticipate this and be enthusiastic about selling on the platform. Ideally, OpenAI's brand acts as a [Schelling point](https://en.wikipedia.org/wiki/Focal_point_(game_theory)), and enough buyers and sellers arrive to reach critical mass.

In your estimation, model builders qua model builders are bad businesses. If a company can train large models and differentiate them, they have a chance. Otherwise, they're selling a commodity. 

-- 

That felt good. You make a note to tell your VC not to invest in any research labs unless they have strong differentiation. Honestly, she probably doesn't have allocation in those companies anyway, but it doesn't hurt to have a view there.  

The next step is to apply coconomic reasoning to generative AI startups as a whole. This is difficult, as there are dozens of different kinds of startups. Fortunately, the coconut knocked out technical knowledge, not chutzpah. 

One lens to analyze AI startups from is, as Ben Thompson [puts](https://stratechery.com/2023/ai-and-the-big-five/) it, commoditizing complements. As the marginal costs of text manipulation/creation approach zero, companies will consume more of it. The insight is realizing companies will also consume more of what's necessary to use low-cost text manipulation. Think of selling spices to chefs when food prices are low, or homebuilding services when interest rates fall. We can think of consumers purchasing "bundles" of goods/services. Ordering a dish at a restaurant is buying a bundle of ingredients, spices, labor, rent, etc.... When the price of the bundle falls, consumers purchase more bundles. The best case scenario is for something else in the bundle to fall in price while your product doesn't. Then, people buy more bundles, and you're selling more products! 

Some products are clearly compliments to AI consumption, like infrastructure. Right now, you remember more about tree nuts than the technical details of implementing AI systems, but that's fine. The relevant fact is there's dirty work around building data pipelines, fine-tuning, cloud providers, and integrating foundation models into products. AI Infrastructure companies have a clear economic opportunity here. The price of the "using AI" bundle will decrease as foundation modelers compete with one another. However, the "infrastructure" part has little negative price pressure. 

AI infrastructure in particular is an appealing startup category for other reasons. Besides reliability, one of the largest problems enterprises have with implementing AI is data security. Nobody wants their proprietary data leaking into some foundation model. The solution is to host your own model on premises or in your own cloud instance (whatever that means). These are, to your hazy recollection, data engineering problems. Companies are also loathe to build the infrastructure in house because it consumes valuable engineering time. Their teams also may not have experience working with specialized data or hardware (like GPUs). These are major reasons to purchase a solution rather than build one. Last, infrastructure is sticky, while the models they support are not. You recall a founder saying it would take "a couple hours" to switch which foundation model is running his product. Altering the entire data pipeline would be more involved. Infrastructure companies, provided they are defensible, look attractive. 

Not all AI startups are as comely. Creating a defensible AI company — infrastructure-based or not — is difficult. Everyone has access to the latest generative AI models for pennies. Use cases the technology obviously fits also look oversaturated. You've seen dozens of AI copywriting tools, email assistants, and text-to-speech companies. Last week, you were pitched on three AI companies in a single day who generate product photos for small ecommerce brands. From a financial perspective, this isn't necessarily a problem. Overcrowded markets aren't bad so long as the winner takes all. Your VC needs a large enough return on the winner to justify dozens of bets in the space. Nothing about AI companies, however, suggests these dynamics. They don't necessarily benefit from network effects, government regulation, brand, or anything else which allows a single organization to swallow an entire industry. If there are 100 AI copywriting startups now, the end result is likely 10 decent AI copywriting companies later who split the market. From a VC's perspective, backing one of the decent companies for a modest return is a failure. 

#### Dizzy prescriptions for your venture capitalist 

The coconut cleared your judgement, though you'll never admit it. Technologically, AI is exciting, but economically, less so. Before you remember what a FLOP is, you dial your venture capitalist to give her a verdict. 

"Listen," you say, "I just had a flash of insight. I'm bullish on AI infrastructure companies. Anything else requires a wide moat before I'll consider it. I know we don't have allocation in any AI labs, but if we do, be sceptical. Those businesses are usually not defensible." 

"Very good, yes," she replies. "Infrastructure is a great space. Everything else is totally overhyped. Defensibility is a great concept to keep in mind here." 

You give a light harrumph before ending the call. Never before have you been this clear-headed. It's probably the ocean air. 



[^0]: For brevity, I'll use "text" to refer to text and images going forward. Sorry. 
[^2]: Basically, your VC is asking if you want to invest in some AI companies. 

[^4]: Attention is really is all you need.













