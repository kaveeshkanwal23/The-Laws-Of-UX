# The-Laws-Of-UX
Design better product &amp; services using the laws of UX as per human pschycology. 

# Introduction
Any design must be human-centered, i,e instead of forcing people to accept a design or an experience, we can use certain laws of human pschycology to design products to which humans are already adapted. Now, this does not mean that you cannot propose a radically different design, but that design must be extensively beta tested before a formal lauch to your larger customer base. But for most cases, it is good to stick to human-centered design.

# Jacob's Law
- Stick to familiar patterns(for eg; navigation, kist view, search, pagination etc) as people have mental models from past UX using different products.
- Understand the mental models of users by creating - user personas, journey maps, conducting user interviews etc.
- User persona generally has 3 parts - Basic Info(name, age, profession etc), details(personas goals), and insignts(direct quotes from the personas).

# Fitts's Law
- Time to acquire a target (eg; a button, combo box etc) is a function of distance to and size of the target.
- Touch targets should be large eough for user to easily distinguish them.
- There must be ample spacing between touch targets.
- Touch targets must be placed in ares which can be easily acquired by the user i,e reachability.
- Distance that a user must travel to acquire the target must be minimum. For eg; have the submit button just next to the i/p fields so that the distance the user travels is minimal.

# Hick's Law (V IMP)
- Show only what is required to be shown to the user at a particular time. Redunduncy and excessiveness create nothing but confusion, it reduces the ability of people to easily and quickly accomplish their task. 
- Break complex tasks into smaller steps to reduce cognitive load. Congnitive load is the amount of mental resources required to understand an interact with an UI.
- Reduce or eliminate things which are not required by the use to complete a particular task.
- As cognitive load increses, the task abandanment by the users also increase.
- Progressively(step by step) introduce new feature so that users do not become overwhlemed.
- The entire idea here is to reduce the mental strain of the user and give him a pleasurable experience while interacting with the UI.
- Make sure that we do not oversimplify too much leading to the point of abstraction. 

# Miller's Law: 
- A user can generally keep 7 (+-2) items in its working memory. 
- Make sure to organize content into smaller chunks so that user can process, memorize and understand it. 
- Chunking: Structuring content into visually distinct group with clear hierarchy so that it can be comprehended easily. 

# Postel's Law
- Be conservative what you show, be liberal in what you accept from the users. 
- Be conservative in how much information you need the users to provide. 
- Users want to feel they're in control. Unnecessary info required from the user must be avoided. 
- A design must be open to extension without changing the whole design. One must only progressively add elemts to a design so that users do not get overwhelmed. 

# Peak End Rule (IMP) 

- People don't remember each and every step of the experience, rather the peak moment and the end moment create a lasting expression in the user's mind. We tend to focus on emotional peaks and the end stage. 

- People recall negative moments more vividly than positive ones.

- Create & use journey maps to find out the emotional peak moments of the user. 

- User jounery map will have the following: 
User persona & it's user story. 
Actions/Tasks done by the persona. 
Emotional layer which captures the emotional peaks of the user at every stage. 
Insights/opportunities describing the needs, desires and pain points of the persona. We can use direct quotes by the persona as well.
Each opportunity to be backed by a metric and it's ownership.
![WhatsApp Image 2025-12-24 at 11 55 53](https://github.com/user-attachments/assets/40c6a58a-ee3b-4c7c-ba7a-d1e39deb2cd4)

# Doherty Threshhold
- UI response times are important for an optimal UX for the end user
- A delay of < 100ms is generally not recognized by human eye.
- Optimal delays are generally around 400ms. 
- Any delay > 100 ms, we must show progress bar, blur-ups(small image placeholders tii the full image is loaded), skeleton screens(till the main content gets loaded), optimistic UI(UI showing progress along with some feedback) and many others. 
- Delay of more than 1 sec tends to increase the cognitive load of the user and he may begin to think of other things. 
- If delay more than 10 sec, it is very important to show the users the time remaining and some info/text of what the system is doing. 
- Sometimes, delays are induced to build trust. For eg; a security checkup on say facebook too more time.
