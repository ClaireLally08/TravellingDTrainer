
# Travelling Dog Trainer

  

This is a website I created to promote a (fictious) dog training business. The Travelling Dog Trainer (TDT) business focus is to educate owners on responsible dog ownership.

  

Finding a dog trainer in Ireland really is not an easy task. There's next to no qualifications required to become a trainer, and often there are more horror stories than good when it comes to hiring a trainer.

  

Taking a special focus on the areas outside of Dublin, and specifically, rural Ireland. The TDT's aim is to educate dog owners by teaching and practicing positive-reinforcement training methods.
> ## Contents
  *[UX](#ux)
  
    - [User stories](https://github.com/clairelally8/travellingdtrainer#user-stories)
    - [Strategy](https://github.com/clairelally8/travellingdtrainer#strategy)
    - [Scope](https://github.com/clairelally8/travellingdtrainer#scope)
    - [Structure](https://github.com/clairelally8/travellingdtrainer#structure)
    - [Skeleton](https://github.com/clairelally8/travellingdtrainer#skeleton)
    - [Surface](https://github.com/clairelally8/travellingdtrainer#surface)
* [Features](https://github.com/clairelally8/travellingdtrainer#features)
    - [Existing Features](https://github.com/clairelally8/travellingdtrainer#existing-features)
    - [Features Left to Implement](https://github.com/clairelally8/travellingdtrainer#features-left-to-implement)
* [Technologies Used](https://github.com/clairelally8/travellingdtrainer#technologies-used)
* [Testing](https://github.com/clairelally8/travellingdtrainer#testing)
* [Deployment](https://github.com/clairelally8/travellingdtrainer#deployment)
* [Credits/Media](https://github.com/clairelally8/travellingdtrainer#Credits/Media)
    - [Acknowledgements](https://github.com/clairelally8/travellingdtrainer#Acknowledgements)
  

> # UX

  

The Navigation bar is always visible when you are on the site, allowing for easy navigation to any part, no matter where you are within the site.

  

The home button and logo will take you right back to the landing page where you can get your bearings and start your journey over again.

  

The About section introduces vistors to the TDT, Claire and also discusses briefly some of the concerns surrounding dog training in Ireland.

  

The Services section clearly discusses the services offered and the length of each session.

  

In the contact page there are ways for users to get in touch with the TDT and request classes in their own local area.

  

In the footer, there are links to all their social media, so you can connect with them more..

  

## User Stories

  

As a client I want to:

- Straight away feel as if I can trust this site to give me the service I want.

- Find out information on the various training services provided.

- See images of clear past clients & current clients.

- Have a way to contact the TDT to request classes nearby.

As the owner, I want to:

- Make known the existence of my business to dog owners alike.

- Visitors can view the range of classes offered.

- receive messages from users when they send one using the contact form.

  

## Strategy

  

My goal was to create a minimalist and user-friendly website as possible, to both showcase my business and educate owners of the risks in hiring a dog trainer throughout Ireland.

  

## Scope

For the user, I wanted to provide an educational service to show and make dog ownership a more positive experience.

  

## Structure

  

The main structure of the website involves 4 main sections, which include images and information about the TDT.

The navbar is positioned at the top and is fixed, so it can be viewed even when scrolling. For a softer viewing experience, the body of the website is an off-white color, with a white navbar, to ensure it stands out from the body.

On small screens, the navbar will collapse into a bespoke "hamburger" style icon of a dogs face. When the icon is clicked, the navbar will expand and show the whole menu.

  

The main landing image has a text animation for special design. The heading text on each page has a shadow effect to really emphasise them.

The images on the about page have a right drop shadow to enhance them also.

  

## Skeleton

  

The website has been structured in four pages, including landing page and the footer.

The wireframes for these can be viewed here:

 -  [Index Page](wireframes/Index.png)
  - [About Page](wireframes/About.png)
  - [Services Page](wireframes/Services.png)
  - [Contact Page](wireframes/Contact.png)
  

## Surface

The color scheme I chose is a minimalist one, with the emphasis on greens which for myself personally signifiy a relationship with the outdoors.


  
> # Features


## Existing Features

About - In this section, the reader the Travelling Dog Trainer learns some of the details regarding my history in dog training, as well as information relating to dog training in Ireland

Services - This section provides users with a breakdown on the training classes provided by the Travelling Dog Trainer and class lengths.

Contact - This section is not yet live, allows the user send a message.

  

## Features left to implement

Future plans for this site include,

- Making the contact page live and functional
- Use of a CNAME (Canonical Name) URL
- Creating a training tips page, which provides detailed information on basic dog training commands.
- A user-login page for clients to view past training class notes and view their 'homework' from each of the training classes as well as a diary entry section to document any behaviors their dog may be exhibiting.

  

## Technologies Used

- HTML,

- CSS,

- [Bootstrap](https://getbootstrap.com/)

 
Also made use of

- [Font Awesome](fontawesome.com)

- [Flat Icon](https://www.flaticon.com/)

- [Google Fonts](https://fonts.google.com/)

- [Animista](https://animista.net/)

- [HTML Validator](https://validator.w3.org/)

- [CSS Validator](https://validator.w3.org/)

- Testing with Chrome DevTools

- Learned from [W3schools](https://www.w3schools.com/)

  
  

> # Testing

The website was tested both after the creation of each section separately but also after its completion. I tested all the functionality in the main browsers that ran on several operating systems: Chrome, Firefox, Safari,  Windows 10, Mac OSX 10.14,  and Android operating systems.

  

Testing during section construction was done primarily with Chrome DevTools, making sure each element works correctly and optimally, including responsiveness across devices. For navbar, I tested the functionality of all links, including the site brand. I also tested the color change of links to hover and toggle and collapse functioning in small devices. 

During testing, I realised the Landing Text was causing responsiveness issues, which was easily fixed by inserting 	display:none; into the CSS of this heading. 

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload.


I conducted several user tests to ensure there was an ease of use with this site, and all users reported the site was well functioning and user friendly.  No users reported the Dog-Icon Navbar as an issue. 

> # Deployment

 
In my account GitHub website, I selected Repositories


I selected TravellingDTrainer from the GitHub Dashboard.

I navigated to Settings and to the GitHub Pages section.

From the Source section, I clicked on the drop-down menu and selected Master Branch.

Once Master Branch is selected, the page has been automatically refreshed, with a detailed ribbon display GitHub Source Saved Pages indicating the successful implementation.

I then decided to use a custom URL, so created a CNAME file with the URL www.travellingtainer.com as the domain, unfortunately there was an issue with the DNS settings and so this feature is one I intend on implementing in the near future.

The live link can be found here - https://clairelally8.github.io/TravellingDTrainer/index.html

To run locally, you can clone this repository directly in your favorite editor, by typing in the terminal the following command:

git clone https://github.com/clairelally8/travellingdtrainer.git
> # Credits/Media

All images used on this page were taken by myself.

The icons used for this site were taken from Font Awesome.

The dog icons on the services page were taken from Flat Icon.

  

> # Acknowledgements

To create this website, I used many resources, like Stack Overflow, the wonderful Bootstrap and of course, every new programmers bible, W3 Schools.

  

The Keyframes for the Animation on the landing page was taken from [Animista](https://animista.net/)
