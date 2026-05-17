# Adding a card

## Step Zero:
- Click Use this template
- Click create a new repository
- Give it a name
- Click create

## Step One:
- Create a suitable PNG A4 image for the front of your card and name it card-front.png
- Create a suitable PNG icon for the browser window and name it favicon.png

## Step Two:
- Upload your icon (favicon) to the repo
- Upload your A4 image to the repo (2480x3508px)

## Step Three:
- Find the example.html file
- Open it and click on the copy icon
- Create a new file called (recipients-name).html
- Paste the text into your new file

## Step Four:
- Change details in your new HTML file

For example change: 

"<title>Happy Birthday, Name!</title>" <br>
To <br>
"<title>Happy Birthday, Dave!</title>"

You must change:
1. The title tag
2. The content of the card (Dear ___ and your message)

- Commit the changes

## Step Five:
- Click settings
- Navigate to pages section

Under Branch:
1. On dropdown select main
2. Click save

### If you don't have a custom domain
Your card is live at username.github.io/repo-name/recipient-name

### If you have a custom domain
- Enter your domain in the "Custom domain" box
- In your providers DNS settings:
  1. Create a CNAME record
  2. Put in a sub-domain or @ for root
  3. Point it to username.github.io

[Learn more about custom domains](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

Your card is live at domain.com/recipient-name
