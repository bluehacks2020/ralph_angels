# Tulay - Bridging Explorers to Local Experts
Team Ralph's Angels
- Ralph Macarasig
- Franz Cesista
---

## Application Description
Tulay is a two-platform app that aims to intiate cultural awareness which can be deepened through cultural immersion, thus forming cultural intelligence. The end goal of the app is to attain a high degree of cultural integrity in the country. The first platform of Tulay is through a Messenger bot with the aim of providing cultural information about the Philippines. This platform is chosen to cater to people who want to be more culturally aware but do not always have access to wi-fi or mobile data. The second platform is geared with a deeper, more immersive cultural experience aimed at people who want to travel but are on a tight budget. The mobile application is intended to connect explorers who want to learn more about other cultures with local experts who are equipped with such cultural knowledge. Through the expertise of locals, an explorer may be able to gain a better understanding and appreciation of another's culture.

## Installation Guide
Only the owner has access to the back-end of the messenger bot that we created due to the limitations of Facebook Messenger API. However, you may refer to our powerpoint presentation to witness how the messenger bot works. To replicate it, you need to follow the following steps:
1. Create a Facebook Page
2. Open [Facebook for Developers](https://developers.facebook.com/) and create chatbot
3. Connect the chatbot to your Facebook Page
4. Connect the chatbot to a Google App Engine backend through Websockets
5. Create a Google Cloud Storage Bucket and upload three files (`states.txt`, `image-labels.txt`, `question-answer.txt`) containing only `123||1`. It's important that you do not add unnecessary whitepasses in any of the three files.
6. Deploy the app through App Engine
7. Profit

The mobile application is developed using Figma. Access the prototype [here](https://www.figma.com/proto/47UGOufBkCJ16NK3fjSiDz/Tulay?node-id=20%3A2&scaling=scale-down). Note that only the "Explorer" option works in the prototype.

## Application Guidelines
The following langauges and frameworks were used in creating Tulay:
- Python 3.7 (with pymessenger and flask)
- Google Cloud Platform
- Figma

## Citations or References
[Bridge Icon by Ben Davis](https://thenounproject.com/search/?q=bridge&i=903064)

Images:

- https://www.sunstar.com.ph/article/1764049
- https://www.yapak.ph/where-to-go/benguet-1411
- https://runroo.com/2019/01/29/tublay-benguet-coffee-harvest-tour/
- http://www.phbus.com/blog/4-of-the-best-coffee-shops-in-baguio/
- https://www.sunstar.com.ph/article/1778097
- http://www.traveltothephilippines.info/2012/01/31/benguet-strawberry-picking-festival/
- https://thetorogichronicles.com/2019/03/07/into-the-strawberry-fields/
- https://madayawwowdagway.com/tnalak-festival-2014-koronadal-city-province-south-cotabato/
