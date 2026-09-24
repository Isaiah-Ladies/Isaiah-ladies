# Isaiah Ladies · New Discipleship Bible Study

Everything the app needs is in one file, `index.html`: all 24 lessons, both images, and the code.

## Put it on GitHub Pages

1. Sign in at github.com and click **New repository**. Name it something like `bible-study`, set it to **Public**, and click **Create repository**.
2. On the new repository page, click **uploading an existing file**, drag in `index.html`, and click **Commit changes**.
3. Go to **Settings → Pages**. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
4. After a minute or two, the page shows your link, like `https://yourname.github.io/bible-study/`. That's the link to share.

## Turn on automatic sending (one time)

Answers are sent through FormSubmit.co, a free service. There's no account to create, but the receiving address must be confirmed once:

1. Open your new link, fill in every answer in Lesson 1, and tap **Send my answers**.
2. FormSubmit emails an activation link to the receiving address. That first test is not delivered, so the app will say it didn't send. This is expected.
3. Click **Activate Form** in that email.
4. Send Lesson 1 again. It now arrives, and so will every submission after it.

Check the spam folder if the activation email doesn't show up.

## Change the email address

1. In your repository, click `index.html`, then the pencil icon to edit.
2. Near the top of the code, find this line and change the address inside the quotes:
   `const SEND_TO = "shelly.m.corwin@gmail.com";`
3. Click **Commit changes**, then repeat the activation steps above for the new address.

To turn off automatic sending, change `const AUTO_SEND = true;` to `false`. Students then use "Open in my email app" or the Copy buttons instead.

## Good to know

- Each student's answers are saved in her own browser on her own phone or computer. They don't carry over to another device.
- Submissions pass through FormSubmit.co on their way to your inbox, so the ministry is trusting that service with the students' answers and mailing addresses.
