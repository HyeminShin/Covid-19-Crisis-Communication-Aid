# BMCC Make-a-Thon 2020 Call for Code IBM Global Challenge

# Project Title
COVID-19 Crisis Communication-Aid

# Inspiration
COVID-19 may have begun in the year 2019, but the virus really became a global concern this year in 2020. One of the most drastic measures necessary to contain the spread of the Novel Coronavirus was self-quarantine. Many have gone months by while we remain indoors, separated from our loved ones, with limited access to limited resources, and facing financial constraints. This situation has led to a communication crisis. Communication is not restricted only to socializing, but also includes access to crucial information. Modern society depends on this flow of information and this is where COVID Comm specializes. Our goal is to resolve this communication crisis by bringing a service to the public that will keep everyone linked to a multitude of resources so that nobody has to feel lost, alone, or in the dark.

# What it does
The goal of our project was to construct a machine learning incorporated chatbot using IBM's tools and integrate it with real-time data scraping from the web in order to provide the most up to date COVID-19 related information. Alexa Integration brings about the added convenience of a natural communication system that will further help the public access COVID related information.

# Challenges we ran into
Integrating the Watson chatbot with Alexa proved more difficult than expected with the biggest hurdle being the connection of the endpoints that allow the Alexa Skill to function as an intermediary between the user and Watson. Ideally, a natural, verbal conversation could be carried out between the user and the Watson driven Alexa Skill, but networking issues prevented us from fully utilizing this synchronicity. The Hypertext Transfer Protocol Secure (HTTPS) requires a Secure Sockets Layer (SSL) to establish an encrypted link between Alexa and Watson, but our team was unable to work out the kinks in time. 

# What we learned
Each one of us took on a different part of this project...
- Hyemin Shin: Watson chatbot development
- Nuhirath Rafthia: Data scraping with Python
- Ryan Najac: Alexa Skills and Watson integration


# Demo Video
<object width="425" height="350">
  <param name="movie" value="https://www.youtube.com/watch?v=DecRMvI8xJM&feature=youtube" />
  <param name="wmode" value="transparent" />
  <embed src="https://www.youtube.com/watch?v=DecRMvI8xJM&feature=youtube"
         type="application/x-shockwave-flash"
         wmode="transparent" width="425" height="350" />
</object>

# Future Plans
1) Expand chatbot capabilities
  - gather further COVID resources such as food bank locations and important news such as financial aid
2) Utilize Live Time Data Scraping
  - gather live time statistical data on the COVID situation
3) Alexa and Watson Connection
  - get Alexa to connect with Watson and communicate back and forth
4) Connectibility of ALL resources
  - scrape further data from the web, and get the chat bot to reflect those changes
  - incorportae live time data all around 
  - create a separate hub on Alexa to act as a communcaiton base for chat bot and live time data

# Built with

- IBM Watson Assistant: A Watson Assistant service that utilizes machine learning and natural language processing to interact with users, provide them with data, answer their questions, and direct them towards useful services.

- Data Scraping: Gathering of up to date information from the web with the help of Python and some of its powerful library tools. Incorporated data from government backed sites such as the CDC, and nyc.gov. All info is true to reported data. 

- Alexa Integration: Amazon’s virtual AI technology assistant, Alexa, has the added benefit of accessibility. By 2021, Alexa stations throughout the BMCC campus will allow students and faculty to interact with Alexa to receive the same information as our chatbot. 

# Team
- Ryan Najac
- Nuhirath Rafthia
- Hyemin Shin
- Dr. Mohammad Azhar
