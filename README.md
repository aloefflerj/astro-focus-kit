# :star: Astro Focus Kit :star:
## Description
:star: Astro Focus Kit is an app that helps you to deal with web procrastination and lack of focus. It is both a chrome extension and a web app.
- 🚫 The chrome extension is as a website blocker
- 📆 The web app is a task manager

## How to start using it

### Production
#### [**Register your account**]
- Go to: [https://astro-focus-kit-client.vercel.app/register](https://astro-focus-kit-client.vercel.app/register) and register your account:

  ![image](https://user-images.githubusercontent.com/51006938/204972559-fde79bed-d2de-4721-90ab-ade59c1224d9.png)

#### [**Install the Extension**]
- Go to the [Chrome Web Extension](https://chrome.google.com/webstore) and search for `Astro Focus Kit`. Or simply access this [link](https://chrome.google.com/webstore/detail/astro-focus-kit-extension/eoepehbjoahjnefiddgjgaenfkfbihgm?hl=pt-br)

  ![image](https://user-images.githubusercontent.com/51006938/205776840-3efe82bf-9822-411f-9f99-84130a488c3b.png)

- Click on `Add to Chrome`
- All good to go! You can now proceed to the following section: [Setting Up the Application](https://github.com/aloefflerj/astro-focus-kit#setting-up-the-application)

Alternatively, you can download the extension and load it manually:

- Download the `.zip` on this link: [Astro Focus Kit Extension](https://agenciakapi.com/astro/extension.zip)
- Save it on your computer
- Unpack it

  ![image](https://user-images.githubusercontent.com/51006938/204973046-07e7f788-1165-4c98-8f46-e9235ee65199.png)
- Open _Google Chrome_
- Type in `chrome://extensions` on the url

  ![image](https://user-images.githubusercontent.com/51006938/204973304-093b5ad5-0d60-4786-aa42-a53df872c937.png)
- Toggle in `Developer mode` at the top right of the screen

  ![image](https://user-images.githubusercontent.com/51006938/204974590-f782ec44-d9b2-4e60-9e9a-92e16bbfa8e3.png)

- Select `Load unpacked` on the top left of the screen

  ![image](https://user-images.githubusercontent.com/51006938/204974667-8f81b3cc-84d4-4735-9572-a44f01ee4693.png)

- Select the unpacked `.zip` folder

  ![image](https://user-images.githubusercontent.com/51006938/204975019-4d4404fb-5a30-4728-954c-38c80184b127.png)

- A box displaying the extension info is supposed to show up

  ![image](https://user-images.githubusercontent.com/51006938/204975133-0585ef50-b213-41b0-a37d-3d3dae602530.png)

#### [**Setting Up the Application**]

- If possible, pin the extension on chrome extensions

  ![image](https://user-images.githubusercontent.com/51006938/204975229-5c19aa53-dafc-4406-b8f3-ba7b4ee5198b.png)
  
- Click on the extension icon and insert your login and password

  ![image](https://user-images.githubusercontent.com/51006938/204975488-94c3378a-6dfd-4423-98ad-e2ddec879133.png)
  
- You should be redirected to main dashboard page. If the login page shows up (:bug: _bug_ 🤦), try and refresh the page.


## How to use it
- On `tasks` page you can register and manage your tasks:

  ![image](https://user-images.githubusercontent.com/51006938/204976331-1361680e-0ffd-4ee7-87bf-fe35f33c36be.png)
  - Tasks are displayed on a week board
  
- On `journal` page you can see your weeks history. (_Weekly tasks and reasons on why you procrastinate_)

- On `metrics` you can see some insights about your procrastination and productivity based on websites blocked and tasks done.

  ![image](https://user-images.githubusercontent.com/51006938/204976736-045dbaa0-c87c-45e2-94bf-085c67f8874a.png)

- On `settings` page
  - You can set websites domain to block
  
  ![image](https://user-images.githubusercontent.com/51006938/204976881-3f28f12e-9409-469a-b3ff-04be0ae50508.png)
  - You can set the timer for when you choose to procrastinate
  
  ![image](https://user-images.githubusercontent.com/51006938/204976997-2e6ace41-a751-4034-90b4-ef60f29a4ffc.png)
- On `quotes` page you can fetch a random motivational quote

  ![image](https://user-images.githubusercontent.com/51006938/204977153-21c6da65-d0b0-4674-9549-dda030e96e14.png)
  ![image](https://user-images.githubusercontent.com/51006938/204977347-88df03be-379c-48be-9561-69773b63363e.png)

## Rules
- If there is a pending task for today, the block extension will be activated

  [**Web View**]
  
  ![image](https://user-images.githubusercontent.com/51006938/204977890-2ec23c78-ef41-4afd-9d0b-5cd034b99c5e.png)

  [**Extension View**]
  
  ![image](https://user-images.githubusercontent.com/51006938/204977709-fd962829-9b59-42da-9faa-0b087e8754b6.png)
  
  - Lets say I have a pending task for today and try to access facebook
    - I should be redirected to the block page
    
      ![image](https://user-images.githubusercontent.com/51006938/204978324-d40feece-6e83-4d03-893d-184bac286fe9.png)
    - You can choose to go back to tasks page and accept the block
    - Else you can choose to keep procrastinating. In this case you should tell a reason on why do you want to do that
    
      ![image](https://user-images.githubusercontent.com/51006938/204978578-1f9da780-1534-418b-a8c6-6551db6d447a.png)
     
    - You will be redirected to the site you were trying to procrastinate and a timer will be shown on the extension displaying how many minutes you have until the site will be blocked again. It is a "procrastination session".
    
      ![image](https://user-images.githubusercontent.com/51006938/204978878-3dba1e16-a30d-4082-af0a-b59506a3dfdb.png)

#### Hope you like it 😉

### Development repos
- [Server](https://github.com/aloefflerj/astro-focus-kit-server)

- [Client](https://github.com/aloefflerj/astro-focus-kit-client)

- [Extension](https://github.com/aloefflerj/astro-focus-kit-chrome-extension)

- [Environment](https://github.com/aloefflerj/astro-focus-kit-env)
