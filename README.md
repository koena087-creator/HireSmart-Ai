# HireSmart AI website (GitHub Pages)

Static site: one HTML file plus chart images. No build step.

## Put it live in 5 minutes
1. Create a free GitHub account.
2. New repository, name it `hiresmart-ai`, set it to Public.
3. "Add file" > "Upload files". Drag in `index.html` and the whole `img` folder. Commit.
4. Settings > Pages > Source: "Deploy from a branch". Branch `main`, folder `/ (root)`. Save.
5. After 1 to 2 minutes your site is at `https://<your-username>.github.io/hiresmart-ai/`
6. Tick "Enforce HTTPS".

## Receive demo requests by email (do this once)
1. Go to https://web3forms.com and enter the email address that must receive the requests.
2. Web3Forms emails you an Access Key.
3. Open `index.html` in Notepad (or on GitHub click the file, then the pencil icon).
4. Search for `PASTE-YOUR-WEB3FORMS-KEY-HERE` and replace it with your key. Keep the quotes.
5. Commit the change. Fill in the demo form on the live site to test it. Check your spam folder the first time.
Free plan: 250 requests a month.

## Receive demo requests on WhatsApp (optional)
1. In `index.html`, search for `27000000000`.
2. Replace it with your number in international format with no + or spaces. 082 123 4567 becomes 27821234567.
3. Commit. The "Send on WhatsApp instead" button now opens a chat to you with the request filled in.

## Check my CV page
Job seekers add a PDF CV. The page reads it in the browser (nothing is uploaded), finds skills, years of experience,
province and expected salary, then scores the person against 5 demo vacancies with the same formula as the Java program.
Use the two sample CVs in the `sample_cvs` folder to demo it.

## Pages
Home, About, Customers, Services (live match engine), Check my CV, Revenue model, Insights, Contact (demo request).
