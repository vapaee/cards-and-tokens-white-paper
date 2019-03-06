# Abstract

There are a lot of places on the Internet where people can post their content. We have specific sites to share videos like Youtube or Vimeo, to post images like Instagram or deviantArt and even text in different blog systems. However, none of them provides the possibility for its users to customize their publications beyond the content itself. In all cases, the publications maintain a format that follows the style guidelines of the system used. At the same time, these users who are the true creators of value are often not rewarded or must go to advertising to monetize their work, staying with a small portion of the proceeds and deteriorating the quality of experience of the spectator. All this without taking into account the fact that these are centralized systems that respond to the particular interests of third parties that regularly participate by imposing censorship and restrictions on the content that can be published.

With the advent of blockchain technology, new systems are being created to solve some of these problems. Now we have alternatives like Stemmit or Synereo, which use cryptocurrencies to reward users who publish high quality content, delegating to the community itself the responsibility of selecting the best jobs and categorizing them in a decentralized and democratic way.

The Cards & Tokens project aims to innovate over these proposals to give alternatives to these problems, taking full advantage of the features offered by this new technology and proposing a new publication format that we will call *Crypto Trading Card*. This new format is not only completely customizable and allows all kinds of multimedia content to be embedded, but it is also an extension of the classic concept of *token* (crypto currency) implemented as an smart contract on the blockchain. In this way, users can make publications as if they were creating a new crypto currency with a predetermined supply, allowing them to monetize their work by selling or auctioning copies of their publication.

Around this new concept we will create an ecosystem that will provide an entertainment platform for users, and will export gamification and content categorization services to other applications generating the ideal context to enhance the value of the cards, beyond the intrinsic value they already have for being an object of collection (due to its content and scarcity).

# Index

- [Abstract](#abstract)
- [Index](#index)
- [Intro](#intro)
- [Problem description](#problem-description)
  - [Customize publication](#customize-publication)
  - [Monetization](#monetization)
  - [Community](#community)
  - [Currency Inflation](#currency-inflation)
  - [Content cleaning and categorization](#content-cleaning-and-categorization)
- [Solution overview](#solution-overview)
- [Solution details](#solution-details)
  - [Modules](#modules)
    - [Vapaée Tokens (vapaeetokens smart contract)](#vapaée-tokens-vapaeetokens-smart-contract)
    - [BG-Box (boardgamebox smart contract)](#bg-box-boardgamebox-smart-contract)
    - [Cards & Tokens (cardsntokens smart contract)](#cards--tokens-cardsntokens-smart-contract)
    - [Content Cleaner Cats (categorizers smart contract)](#content-cleaner-cats-categorizers-smart-contract)
  - [Economy](#economy)
    - [Tokens](#tokens)
    - [Rewards](#rewards)
    - [Inflation](#inflation)


# Intro

In the last two years we have seen a vertiginous increase in fundraising through the implementation of the ICOs, which has only been possible after the invention of the blockchain and smart contracts. However, this method is reserved only for companies and groups of full time developers devoting a great effort to make a value proposal with a large project. It is very difficult (if not impossible) for a single person to organize a successful ICO and raise money.

Cards & Tokens provides to content creators with a new publication format that allows them to tokenize their work and have *copies* of their publications. Then they can sell, auction or give away all o some of the copies in exchange for tokens to monetize their work. This way any youtuber, instagramer, photographers, illustrators, designers, musicians and all kinds of content creators can have their own *Initial Card Offering* (ICO) for each publication they make.

Within the world of crypto currencies, the tokens take their value from the project to which they belong. As the project progresses and its popularity increases, it is expected that the value of the token will rise as well. In the context of Cards & Tokens, the cards not only obtain their value from their content and scarcity, but they will obtain points as their popularity rises that will make the card to level up. Within this platform these cards will be object of gaming in many different proposals of entertainment and the higher the level of the card the better for its owner.

# Problem description

## Customize publication

In many cases, content creators are artists who are interested in having their work published in the best possible way. However, all content platforms are very rigid in their aesthetic patterns, making all publications look alike. There are few cases where the user can put background images, change the colors of the texts, much less design a structure with sections and menu buttons.

In Cards & Tokens, artists can customize every aspect of their publications, namely *Crypto Trading Cards*.

## Monetization

Classic monetization models are based on exposing advertising to the viewer, degrading the experience of visualizing the content. The most used method, is to force the spectator to watch an ad-video before being able to access the chosen video, which sometimes ends up driving away the user.

Other systems such as Steemit have tried another type of financing based on the faculties of crypto currencies. However, they have face other types of problems that derive from their particular economic design, where each *like* is literally worth money.

Cards & Tokens provides a much more complex system where many actors participate to generate an ecosystem where the wealth is much better distributed.

## Community

It is very difficult to get a large number of followers without investing large amounts of money in advertising or being a super star. You have to improve your work more and more to make your content even better to offer more to the end user.

On the other hand, censorship is one of the potential problems faced by many influencer. It is easy to find cases where the platform decided to close a particular account and the user owner of that account lost all its followers.

Cards & Tokens will be built with eosio blockchain technology which is executed in a distributed manner by smart contracts, which guarantees the non-censorship of the accounts. At the same time, it offers a very new fancy format for displaying content, which can help attract many new followers.

## Currency Inflation

On the Steam platform, the inflation of the currency was chosen to finance the rewards for the authors of the posts. However, there are very few services offered by that platform, which has degenerated in its gradual currency devaluation over time.

Cards & Tokens will offer many services that can be purchased only with the main currency CNT. All the tokens paid for Services will be burned and taken out of the total supply, which will counteract the inflation.

## Content cleaning and categorization

When you have a centraliced platform like facebook os youtube, you will face specific rules that you must follow and there will be a police to hunt you down if you don't. But in decentrliced systems like Steemit we don't have that kind of content depuration. Instead we have auto-proclamed depurators with a lot of power (whales) imposing their will and their ethics. But the platfor was not thoght with this mind, there's no written rules for that.

Cards & Tokens dedicates a complete submodule to solve this cleaning and categorization problem, which involves a subeconomy with services and rewards, reaching a consensus over content depuration.

# Solution overview

Cards & Tokens will be a unique platform in its genre where users can collect, trade and play with other users' publications. This crazy idea will only be possible thanks to the new publication format introduced by this platform that is called *Crypto Trading Card*. This format allows users to embed their digital content in a crypto-card from which they can then sell or auction copies to monetize their work.

In other words, this platform propose to tokenize the publication itself in the format of a *Crypto Trading Card*. Each publication will be a card and it's visible for everyone, like a video on youtube (in fact, the card could embed a video from youtube). But only those who have a copy of that card will be able play with it, collect it, burn it or sell it for tokens.

This new publication format is completely customizable and has a deliberate gaming card aspect because copies of this new concept should be included more and more in new gaming proposals that will come to the platform. This will create an ecosystem where the best cards will be highly demanded provoking high speculation over the cards' prices.

Finally the platform will provide lots of services to other Dapps which is going to help to consolidate a mass population over its markets (cards & tokens respectively).

# Solution details

The whole platform is a complex system composed by several modules, each with a specific roll and duties. This modules are encapsulated in different smart contracts interacting with each other through messaging to make the whole system work. Each of them will store the data related to the module and export certain group of actions to be called from outside the module.

## Modules

- ### Vapaée Tokens (vapaeetokens smart contract)

    Vapaée is the company behind this project and will be responsible for many more projects to come. Each introducing its own token. All those tokens will be implemented in the **vapaeetokens** module.

    It implements the basic *transfer*, *open*, *issue* and *burn* default curency actions but add some other features like auto-claim airdrop, token exchange orders, token auction, token lock, token staking and much more.

- ### BG-Box (boardgamebox smart contract)

    Board Game Box (or BG-Box) it's a low-level module that exports several abstract gamification services and Cards & Tokens consumes some of those services.

    On the most basic level, BG-Box provides a profile implementation where any blockchain account can register as a *publisher* or as a *dapp* (with a smart contract on the chain). Those profiles are the actors of this platform and will be referenced as owners and authors of whichever other concept represented in any module.
    
    One of the most low-level services of this module is the abstract concept of item and its containers. This modules implements this two concepts, allowing registered profiles create items and even define new ones. It also manages the ownership and authorship of any instance of any item or container.

    It also manages the capacity of containers. It asserts that every virtual object has its own place inside a correct container belonging to its owner, and that no place is double-used by two different objects (unless its item type definition says so).

    Cards & Tokens acts like any other client for this module. It registers a profile as a *dapp*, and defines the *card* as an item and two kind of containers: the *inventory* and the *album*.
    
    Users registered as publishers, will be able to create concrete cards giving them a unique name within the *dapp* name space. After that, each author of each card will issue copies of those cards for selling them, autioning them or for giving them away.

    Finally, other users can collect and trade those copies and everything is managed by this module.

- ### Cards & Tokens (cardsntokens smart contract)

    The Cards & Tokens module manages all specific logic to create a platform where every user may create cards using any kind of content and then have copies of those cards and trade them of collect them in the albums and win prizes.

  - #### Cards

    The *card* concept (which is an abstract item defined in BG-Box) is really a post from a publisher profile using the *Crypto Trading Card* format, that means it has a preview thumbnail image and may display some content if it is acceded.

    For the preview image we chose a gaming card design deliberately, because we wanted every publication to be perceived as a playable and collectible object.

    On the other hand, we want that card to look really good when deployed, and this could only be achieved by letting the authors to customize the maximum possible.

    That's why we have a very complex data-driven template system implemented in this module that allow us to describe every possible display structure and style that the author would imagine.

  - #### Cards Level

    At the moment that a card is published, it has none contact with the public. Therefore has zero points accumulated and its level is zero.
    
    Once made public, a card will start receiving points, mathematically deduced from the social acceptance and public evaluation.

    It will start to receive *likes*, *comments* and being shared with more and more people.
    
    Copies of this card will start being sold and bought in the market, creating trading history for each card.

    Finally, if the card is worth it, some *cats* (categorizers) will take the job to categorize it and giving it a fair score.

    With all this data obtained from the interaction between the cards and the public, the platform calculates the points any card should have which determines the card's level.

  - #### Albums

    Another concept implemented in this module is the album in all its flavors. Any Album should be considered as a specific topic, to which any user can subscribe and have her/his own collection of cards.
    
    All albums are made by a user who sets a specific filter that defines which cards are allowed inside the album. All cards are supposed to have a categorization that defines which type of content is has. The creator must also configure how many pages will have the album, how many slots on each page and where each slot will be located on the page.

    Any body can define a album and any body can start collecting cards for a specific album. All the collectors of the same album compete with each other to have the most valuable collection for that album. 

    The top 10% most valuable collections will receive prizes. That means tokens for the owners of the winners collections (because they gather the best cards together in the same collection), tokens for the authors of the winner cards (because they created great cards) and tokens for the album's authors (because they gather together a lots of collectors under the same topic).

    As it was mentioned earlier, there are different types of albums. Each kind of album satisfies a specific kind of need.

    - #### Collection
  
      A collection album is an album tat allows to collect any cards of a specific topic. A user collector may put a card inside a collection album if the card satisfies the album's filter. If so, the owner of the copy may put the card in whichever empty slot of any page of the album.
  
      This last thing make more sense when we have some albums with special slots o pages, that modify the points a the card grants if it's hold on one of those slots. This gives more gaming complexity to the collection point competition.
  
      Generally there will be much more cards availables (accepted by the album's filters) for this kind of album than the amount of slots the album has. That means that the users will have more cards that slots and will have to choose which ones to use or how to combine them to get the maximun score. That will drive speculation and fun.
      
      All collection cards will have limited amount of copies (maximun supply) and the magnitude will be very low (tens or handreds) which makes them all rare.
      
      This album can be either open or closed.
  
    - #### Numbered
  
      Numbered albums are like regular old classic paper albums and they are closed albums by definition. Everything is made by anticipation and all the content is ready to hit the public at the same time.  
      
      Also, numbered cards are infinite supplied, which means that the author may sell infinite number of envelopes of random group of several numbered cards.
  
      In this kind of album, every collector has the same collection of cards, so the winners will be the top first to fill the album (having several check points. eg: rewards for the top first complete half album an full album).
  
    - #### closed
  
      If you are a contnet creator this is kind of album will fit you best. 
  
      You can create collection closed albums with showing your own style in every page, customize images and colors, with a fixed amount of slots. The filter of this allbum will only allow cards made by you.
  
      As time goes by, you will be publishing more material, each having its own destiny and reaching a certaing level. Your followers will speculate with the value of your cards, trying to adquire some copies of the most promising ones to put in their collection of your album.
  
    - #### open
  
      If you create cards of a specific topic but you wellcome cards from other authors, you can create an oppened collection album. Your followers may use your cards to put in the album or use somebody else's card if it accepted by the album's filter.
  
      - #### temlate
    
        A more specific kind of open album is when you proide a template to use by anyone who attempt to creat a card for your of album.
    
        The filter of this album requires for the card to use the template provided by you for this goal. This way you can accept other people's card and assert all cards at least follows the same pattern determined by the template.

- ### Content Cleaner Cats (categorizers smart contract)

    *Content Cleaner Cats* is a submodule of this platform dedicated completely to score, depure and categorize any kind of content in a decentralized, democratic and censorship-resistant way.     
    
    Playing with the word *categorizer*, we call *cats* the users who dedicate some time and effort to perform the difficult task of cleaning any content published by other users.

    In the context of Cards & Tokens, this allows us to have a categorization of each card, not made by the card creator but by *cleaner cats* who will be rewarded for the job.

    To carry this task on, this module implements its own economic model based on its own internal token.

    


# Economy

## Tokens

## Rewards

## Inflation

