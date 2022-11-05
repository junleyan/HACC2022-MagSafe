# MagSafe 
A web address-shortening platform that helps state agencies share web content in a more organized and secure manner. 


# Deployed Solution
`https://magsafe.vercel.app/`

# MagSafe Login Instructions
To login, please enter the provided username and password below and click Enter.
- username: `User1`
- password: `pass1`

# MagSafe Walkthrough with Andy Chen 
Click on the image below to redirect yourself to the YouTube walkthrough video.

[![Tutorial Video](https://i.ytimg.com/vi/5oZZtCWeOO4/maxresdefault.jpg?sqp=-oaymwEmCIAKENAF8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGGUgZShlMA8=&rs=AOn4CLBDHHhZF0azhNfLrJ_maznQLIJnqg)](https://youtu.be/5oZZtCWeOO4)


# Inspiration

We recognized the risks involved in using public web address-shortening services such as Bitly and TinyURL. Although these services are free and convenient to use, they are often a precursor to data breaches and ransomware attacks. To combat this issue, we designed our web address shortening platform intending to offer better security and to protect the State of Hawaii’s branding.

# What it does

Our application has 3 primary functions that are key elements of a web address-shortening service. Access to these functions is protected through the authentication of a username and password.

- Users can create shortened web addresses with their chosen aliases that redirect them to their inputted destination web address.
- Users can modify their shortened web addresses with a newly inputted alias.
- Users can delete their existing shortened web addresses.

# How we built it

The tech stack of this application is composed of FastAPI, React.js, and MongoDB, and the application is deployed on Vercel. Throughout development, we used GitHub for version control to collaborate in an organized manner.

# Challenges we ran into

Due to our prior lack of experience working with the JavaScript language and its other development frameworks, we struggled to understand JavaScript concepts such as promises and hooks. As a result of this, we stumbled on establishing a modular code structure that could have made future development more efficient.

During the initial development phase, some team members had trouble merging code and creating branches on GitHub as they were unfamiliar with using these features. In addition, we faced major hurdles trying to schedule team meetings due to busy schedules.

# Accomplishments that we're proud of

Though we only had intermediate knowledge of react hooks, we were successful in creating a fully dynamic website that changes with user inputs and adapts to the viewport. We also had major successes with developing the backend as we were able to establish an efficient and modular code structure that made development easy. Overall, we saw this project as a major milestone and accomplishment in regard to our web development skills as we were able to gain experience working with a large-scale project and experience the whole development cycle.

# What we learned

We learned how to design and develop a backend that was convenient to interface with and develop upon. Not only that, we were able to learn and expand our toolsets with professional development services such as MongoDB and Vercel. The hackathon enabled us to step out of the comfort of coding in Python and learn and gain hands-on experience with another unique and sophisticated programming language.

# What's next for MagSafe

We plan to implement more security features such as security images, 2-factor authentication, and rate limits to the API to increase the security level of our application. Given enough time, I wish to implement more user features such as the ability to view click counts and a display chart of the shortened URLs' referrers.
