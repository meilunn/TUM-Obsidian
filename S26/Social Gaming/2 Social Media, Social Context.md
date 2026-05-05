## What is social media? 
service vs platform?
- Social media **service**: Web-based service supporting _social interaction_ via the *generation* and *exchange* of large amounts of content by a *broad* non-IT-specialist *set of users*
- Social media **platform** is "functioanlly coherent bundle of Social Media services"

Social Media service / platform instance
- _instance_ of service or platform with an associated _user base_ and _information space_ 

Social Media service class (examples): Wiki, Blog, discussion board etc

Social Media service software
- *implementing* Social Media services
- e.g. mediaWiki implementing Wikipedia

Social Media platform software
- *implementing* Social Media platforma
- e.g. Elgg implementing Social Networking platforms

Social Software
- Social Media service software $\cup$ Social Media platform software

#### Was ist social media NICHT? 
z.B: WhatsApp -> ist gerichtet, nicht 1 zu N mit N groß und unbekannt
-> Wenn N zu klein

Wikipedia social media? Randfall. Producer group ist eher klein, aber schon groß und heterogen

Social media is communication, comm is not always social media


### Definition issues

CSCW software
- collaboration is form of social interaction
- CSCW software/services (e.g. GIT, Google Docs), professional collaboration platforms (e.g. company social networking platforms)
- -> *Social Media?*

Social Media
- involving user-generated *content* that is "created *outside of professional* routines and practices"
- -> constant blurring between professional & non-professional -> Influencer

user-generated content in social media
- should "show a certain amount of *creative effort*" 
- should be published to a *larger audience* 
- -> exclude classic messaging servies (e.g. email) from social media? 

#### Criticism
Web 1.0 *already providing* all basic prerequisites and characteristics of **collaboration, social interaction and distributed content generation and exchange**


> -> "Social media" is not clearly defined


## Social Media Characteristics

Openess
- admissibility, low technical barriers

Content
- subject to constant change

More interactive 
- e.g. enabling back-channeling

Fast dynamics
- emergent social effects
- e.g. triggering initiatives in cases of disasters

Social information processing paradigm
- collectively solve problems beyond individual capabilities

> users = "prosumers" (producer + consumer)


Users **collaboratively explicate / model relations** of various kinds

![[Pasted image 20260422144153.png|536]]

**Social Context**: 
- models of any aspects of social interaction having a relation to IT systems

# Technologies

general enabler technologies for Social Media: technologies for building general *Rich Internet Applications* (RIAs) or *Web‐applications* 

- basic Web protocols (e.g. HTTP(S))
- languages for declarative representation of structure, actual content, and format of content (e.g. HTML5, XML + related (e.g. XSLT), specialized XML languages (e.g. GML))
- Semantic Web languages (e.g. RDF(S), OWL, SPARQL), Social Semantic Web Ontologies (e.g. SIOC, FOAF)
- client-­‐side technologies (e.g. JavaScript, JSON, AJAX)
- server-­‐side technologies (e.g. NodeJS, PHP, JSP, Python Django, Ruby on Rails, Spring, Databases)
- syndication and mash-­‐up of content (e.g. RSS, Atom)
- Social Software (e.g. Elgg, MediaWiki)


# Social media classes

All social interaction in Social Media may be viewed as forms of communication 
-> characterise social media classes via classification system for communication

Social media services and platforms will typicalls support communication that is m:n or 1:n (with m, n large), **non-commercial**, and has **implicity specified** audience


## Axes characterising forms of communication

Cardinality of persons involved in a typical communication act {1:1, 1:n, m:n}

Audience specification
- {direct (explicitly specified), indirect (implicitly specified)}
- specific dedicated receiver / list of receivers vs. open set of receivers, possibly formally or informally constrained e.g. via certain properties

Channel directedness
- {unidirectional, bidirectional}

Sender anonymity
- {non-anonymous, anonymous}
- the identity of the sender(s) is or is not known to the receiver(s)

Threadedness
- {threaded, non-threaded}
- do 'reply-type' relations exist between representations of communication acts? 

Content type
- {textual, graphical, video, contextual (locations, social relations, user-item-relations etc.)}

Transmission style
- {stream, discrete}

User Interface / Device / Usage Pattern
- {mobile, laptop, desktop}

Goals (may overlap)
- higher level of abstraction: {informing or being informed, create or gain awareness, collaborate, chat, etc.}
- lover level of abstraction: {find a partner, maintain + expand social network, generate + manage ideas, exchange movies or music, entertain or be entertained, explicate and organize knowledge, etc.}

Commercialization 

Speech Act characterization 
- {locutionary act, illocutionary act, perlocutionary act}
- saying smth, doing smth by saying smth, achieving and effect by saying smth (e.g. declare war)

Context
- {social contexts, location context, psychologial states, further media context etc.}

## Classes

 with an emphasis on certain forms of communication 
 -> supported typical communication form, typical goals

Blogs
Microblogs
Wikis
Discussion boards (superclass: information services)
Social Games

### Collaboration oriented classes

Open innovation platforms, Collaborative Creativity services and platforms
- overlaps with: social networking platforms
- typical goals: develop and incubate ideas and project proposals

(Revision control)

### Social networking & related classes

Social networking platforms
Mobile social networking platforms (kind of obsolete)
Location-Based social networking platforms/services (overlaps strongly with mobile social networking)
Profressional social networking platforms
Partner finding / dating or friend finding platforms

### Goal oriented classes

Altruistic Community platforms
Political community platforms
Knowledge codifications services 

### Classes with emphasis on content

Events services / platforms
News
Social search
etc

## Non social media classes

Messaging
IP Telephony
Chat

-> typically m or n too small


# Social games

Social digital game
- a game (in the sense of the definitions and characterizations of game as in this lecture)
- makes substantial use of *digital computers* (def and char of digital game as in this lecture)
- makes substantial *use of social context* / at least substantially involves *more than one player* (in its social & interactive gameplay, game mechanics, or rules etc)

-> Distinction between social media & social game is not fully sharp

#### Important common aspects social media <-> (Social) Games
- mostly "outside" serious life, *leisure time oriented*, 
	but both increasingly many "serious forms" (-> Serious Games, company SN, etc)
- *communication* as important element
- defined set of *rules*
- *emergent* mechanics & dynamics; transformative use
- *transmedial* access patterns, blurring real / virtual world
- complex game worlds <-> social information spaces
- parallels in aspects of *motivation*, flow

#### Distinctive aspects

games
- main purpose entertainment
- stories and the imaginary
- rules more explicit
- mostly dedicated time to playing

social media
- main purpose communication, not only entertainment
- mostly related to user's real life
- rules often more implicit
- mostly done "nebenbei"


-> "unifying" class: leisure time oriented applications, services & platforms
	-> for this class: social context on various temporal scales play important role
	-> we will define social context and investigate the **role, applications and detection** of **social context** using the example of **Social Networking**

![[Pasted image 20260505124029.png|362]]


# Contextual Social Networking

- paradigm in Social Computing

- Users' main goal: 
	- maintaining and expanding their social network via comm
- users **explicate** and maintain **explicit model of social relations** (-> social network) and **user-item-relations** (likes, comments etc.)

- users socially interact using **bundle of Social Media services** 
- users have **personal information spaces**
	- sets of items associated with users that they exert control over or whose relations (user-item) they exert control over
- user has **personal profile** 
	- publicly accessible sub-space of p.i.s: used as personal reference for introducing a person or used as ref point for SN services (e.g. awareness services)
- **communication**: non-anon
- content: mostly textual + photos + contextual; non-commercial; discrete transfer

# Social Network

Def (informal) Real World Social Network:
-  set of humans together with all aspects of their social relations

Initial def Social Network Model Framework
- mathematical rep (modelling) language for modelling real world social networks (often a graph formalism)

Initial def Social Network Model: **graph G=(V,E)**
- **nodes V**: represent humans (actors)
- (undirected) **edges E**: represent binary social relations (ties) $E \subseteq {V \choose 2}$

Def Social Network
- **instance** of Social Network Model

> **Distinguish** between
> Social networking 
> Social networking platform
> Social networking platform instance
> Social network


### slightly refined Social Network Model

Graph $G=(V, E, P_{V}, P_{E}, f_{P_{V}}, f_{P_{E}})$

- **Nodes** $V=\uplus V_{i}$ 
	- humans (actors) of diff sorts (-> modes) $V_{i}$
- **Edges** $E \subseteq V \times V$; $E = \uplus E_{i}$
	- directed binary social relations (ties) of diff sorts $E_{i}$
- $P_{V}$: Set of **Node Profiles**
- $P_{E}$: Set of **Edge Profiles**
- $f_{P_{V}}: V\to P_{V}$
- $f_{P_{E}}:V\to P_{E}$

![[Pasted image 20260505124049.png|277]]

#### Social ties

Edge profiles - types of social relations (examples)
- friendship, kinshin, professional realtions, ...
-> large **ontologial fredom**, often hard to define precise semantics for edges

Alternative characterisation: use multiple axes (intensity, valence, hierarchity, ...)


# Social Networking Services


Awareness / contextual
- services for personal **social network management** (adding friends etc)
- **awareness** services on **social network** (network analysis, alerts etc)
- services for **privacy** management
- for **group** management
- for **ratings**, comments

Direct communication
- synchronous + asynchronous, threaded + non-threaded, 1:1, 1:n, n:m, ...
- e.g. chat, messaging

Information
- personal **blogs** + microblogs
- bulletin **boards** (e.g. Facebook Chronic)

# Mobile social networking + Context

Distinction SN <-> MSN
- MSN is a **form of SN** with **mobile UI** AND **acquisition** and **use of contexts** induced by the mobile interaction scenario (deep embedding into all day life) via **sensors** conceptually connected to the mobile usage scenario (e.g. part of the mobile device)

Context
- *where* you are, who *you* are with, and *what* resources are nearby -> more than just the user's location
- any information that can be used to characterise the **situation** of an **entity**
	- entity is a person, place or obj that is considered *relevant to the interaction* between a user and an application, including the user and applications themselves

Context Awareness
- A sys is context-aware if it **uses context** to provide **relevant** info and/or services to the user, where relevancy depends on the user's **task**
- Context is an **operational term**
	- something is context bec of the way it is used in interpretation, not due to its inherent properties

Context classes
- Computing, user, physical, temporal
- identity, location, status

Active / Passice Context Awareness

higher lvl / lower lvl context

Dynamics
- context : rapid changes
- personalization info: slower changes

Temporal distinction
- long, medium, short term

## Context classes for Contextual Social Networking (CSN)

Physical Context
- at user's spatiotemporal location
- independent of user: lighting, temperature etc
- also computing context:
	- at user's spatiotemporal location
	- independent of user: available bandwidth etc

Individual Context of user
- location, speed, disabilities, personal physiological params etc
- computing context 
	- involving nature of the device(s)
	- state of applications running, precise state of interaction of user with device or app

Social Context
- refers to characterizing the **social nature of the situation** a user if currently in
- *models* of any aspects of *social interaction* having a relation to *IT systems*
- short term
	- low level: e.g. set of ids of people in Bluetooth range
	- higher level: e.g. social situations
- long term
	- low lvl: e.g. friendships in Facebook
	- higher lvl: e.g. dense Social Network groups the user is part of


#### Facets of social context
![[Pasted image 20260505122644.png|522]]

#### Context classes for SN (Applications)

- collaborative filtering: dampen ratings if not given in ,atching context
- awareness: social + location
- privacy settings
- social lifelogging
- etc


# Decentralised social networking + social semantic web

## Data-Silo Problem

Solutions
- API-based: e.g. Google open social
- decentralised social networking
	- P2P SN
	- Social sementic web

![[Pasted image 20260505123507.png|536]]


# Social Computing

Two main directions
- Mining "Big Data" from social media
	- crawl large datasets, analyse them with statistical methods (data-mining) and / or model them with machine learning models (-> usage)
- Construct games and social media making intelligent use of social contexts on various levels of abstractions / on various temporal levels

# Questions

- Define “Social Media Service” and “Social Media Platform”!
- Can CSCW software and the collaboration oriented Social Media classes be considered Social Media software / Social Media? Briefly discuss!
- Characterization of Social Media services in terms of the supported forms of communication: Name and define four different characteristics (axes)!
- Social Semantic Web: What is the nature and function of OWL, SIOC and OPO?
- What are reasonable classes of Context in Social Networking and Mobile Social Networking? Briefly explain!
- Social Networks: What information can be modeled in edge profiles?
- What are main differences between Blogs and Microblogs?
- Define “Social Game”!
- Name and briefly explain three common aspects of Social Games and Social Media!
- Name and briefly explain three characteristics of Social Networking!
- Define Mobile Social Networking!