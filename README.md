# Children of Indonesia

Children of Indonesia (COI) is a photography journal created by Ano Jumisa, who travels throughout Indonesia to capture the stories and experiences of its children. This project draws inspiration from Human of New York, a similar project by photographer Brandon Stanton, but with a specific focus on Indonesian children.

Through stunning photographs and engaging narratives, COI showcases the beauty and richness of childhood in diverse regions of the country. Ano ventures beyond the joyful and exciting moments to reveal the unique stories and challenges faced by children in different parts of Indonesia. This website provides a comprehensive look at the project, offering:

-   Complete stories: Go beyond the social media snapshots and delve into the full narratives behind each child's experience.
-   Travelogue: Join Ano on his journey across Indonesia, discovering the diverse landscapes and cultures that shape children's lives.
-   Behind the scenes: Explore the creative process, photography techniques, and challenges faced in capturing these authentic stories.
-   Project uniqueness: Understand what sets COI apart from other initiatives and its contribution to raising awareness about Indonesian children's lives.

## Features

-   Hidden navigation
-   An image of a kid riding a large eagle decoration
-   CSS animation for grid sections, and
-   A carousel featuring highlighted children's images with a hover effect.

## Navigation Bar

Using a curtain menu in the navigation, the navbar is intentionally hidden from view, allowing the hero image to be displayed in full screen. To access the navigation menu, users can click the three dots at the top of the screen, causing the menu to slide down from the top, covering the entire screen.

## Main Section

For the main section, I used a 3x3 grid to contain three sections of image showcases: one big image in the middle section and two small images along with their stories on the left and right sides.

The left and right side containers can be animated on hover. The left side image will move 300px to the top, and the right side image will move 300px to the bottom from their original positions.

## Color Reference

| Color         | Hex                                                              |
| ------------- | ---------------------------------------------------------------- |
| Example Color | ![#FBA834](https://via.placeholder.com/10/FBA834?text=+) #FBA834 |
| Example Color | ![#333A73](https://via.placeholder.com/10/333A73?text=+) #333A73 |
| Example Color | ![#387ADF](https://via.placeholder.com/10/387ADF?text=+) #387ADF |
| Example Color | ![#50C4ED](https://via.placeholder.com/10/50C4ED?text=+) #50C4ED |

## URL links

-   [GitHub Repository](https://github.com/RevoU-FSSE-4/module-2-anojumisa)
-   [Website URL](https://childrenofindonesia.site/)

## Lessons Learned

This project focuses on learning how to create a website using CSS, particularly incorporating grid animations. The goal is to gain hands-on experience in applying CSS techniques to enhance website design and interactivity.

## Lighthouse Score

In this assignment, I achieved a high overall score in the Google Lighthouse audit, as evidenced by the following screenshot:
![Google Lighthouse Score](/readme%20assets/Screenshot%202024-03-01%20195201.png)

One approach to improve performance, as suggested by Lighthouse, is to convert PNG images to WebP format.

## Deployment

### GitHub Actions

In this assignment, I used GitHub Actions to automate deployment to Netlify.

Here's a breakdown of the initial GitHub Actions steps:

1. Verify Remote Repository: I used `git remote -v` to check my current remote repository.
   ![git command - remote repository](/readme%20assets/Screenshot%202024-02-29%20195019.png)
2. Switch to Main Branch: I switched to the working branch (main) using `git checkout main`.
   ![git command - checkout to main branch](/readme%20assets/Screenshot%202024-02-29%20190605.png)
3. Check for Changes: I checked the status of tracked work updates with `git status`.
   ![git command - status check](/readme%20assets/Screenshot%202024-02-29%20190825.png)
4. Stage Modifications: Since there were modified files, I added them to the staging area using `git add .`.
   ![git command - add files to the staging area](/readme%20assets/Screenshot%202024-02-29%20194754.png)
5. Commit Changes: I committed all changes using `git commit -m "descriptive message"`. In this case, the commit message was `"adjust background image size"` to reflect the change made.
   ![git command - committing changes](/readme%20assets/Screenshot%202024-02-29%20195048.png)
6. Push to Remote Repository: Finally, I pushed all changes to the remote repository using `git push origin main`.
   ![git command - pushing changes to the remote repository](/readme%20assets/Screenshot%202024-02-29%20195117.png)

### Website Hosting

The next step involves hosting the final website on a provider, Netlify. Here's how I did it:

1. Sign Up on Netlify: I signed up for an account on Netlify.
   ![Netlify landing page](/readme%20assets/Screenshot%202024-02-28%20211008.png)
2. Connect to GitHub: I chose the "Sign up using GitHub" option to connect my Netlify account to my GitHub account.
   ![Netlify sign up page](/readme%20assets/Screenshot%202024-02-28%20211108.png)
3. Import Existing Project: On the "Sites" tab, I clicked "Add new site" and chose "Import an existing project."
   ![Netlify add sites page](/readme%20assets/Screenshot%202024-02-28%20215814.png)
4. Deploy with GitHub: Since my code repository is located in GitHub Classroom, I selected "Deploy with GitHub."
   ![Netlify add new site page](/readme%20assets/Screenshot%202024-02-28%20215907.png)
   ![Netlify deploy project page](/readme%20assets/Screenshot%202024-02-28%20215933.png)
5. Configure Netlify and Select Repository: I followed the prompts to configure Netlify on GitHub and then selected the specific repository containing my website code.
   ![Netlify repository option page](/readme%20assets/Screenshot%202024-02-28%20220140.png)

6. Continuous deployment: This is a feature where all code changes are automatically deployed to the Netlify hosting provider after being pushed to the remote repository. Once deployed, the changes are reflected on my website.
   ![Netlify continuous deployment section](/readme%20assets/Screenshot%202024-02-29%20224440.png)

7. Enter Site Name and Deploy: Finally, I entered a desired site name and clicked the "Deploy" button at the bottom.
   ![Netlify site name option page](/readme%20assets/Screenshot%202024-02-28%20221221.png)
   ![Netlify web deploy page](/readme%20assets/Screenshot%202024-02-28%20221253.png)

### Custom Domain

Next step is to publish my website using a custom domain. I purchased a domain name using Niagahoster, a local domain registrar in Indonesia. Here's the process:

1. Choose domain name: I accessed the "Domain" section through the navigation menu on Niagahoster's website.
   ![Niagahoster landing page - ](/readme%20assets/Screenshot%202024-02-28%20211918.png)
2. Check availability: I typed in my desired domain name and checked its availability.
   ![Niagahoster domain availability check](/readme%20assets/Screenshot%202024-02-28%20212240.png)
3. Select the domain: I chose my preferred domain extension (e.g., ".site").
   ![Niagahoster domain extension option](/readme%20assets/Screenshot%202024-02-28%20212340.png)
4. Create an account: I created an account on Niagahoster to complete the purchase.
   ![Niagahoster create account page](/readme%20assets/Screenshot%202024-02-28%20212455.png)
5. Complete payment: After navigating to the payment page, I completed the payment process.
   ![Niagahoster successful domain purchase](/readme%20assets/Screenshot%202024-02-28%20213423.png)

### Publish the Website

The final step is to connect my custom domain to the website hosted on Netlify. Here's how I did it:

1. Find Netlify nameservers: I accessed the Netlify settings and located the four nameservers provided for my website.
   ![Netlify DNS domain name servers](/readme%20assets/Screenshot%202024-02-28%20222450.png)
2. Update Niagahoster nameservers: I logged into my Niagahoster account and navigated to the "Domain Management" or "DNS Management" section. Then, I replaced the existing nameservers with the four nameservers copied from Netlify.
   ![Niagahoster name servers input](/readme%20assets/Screenshot%202024-02-28%20222837.png)
3. Wait for propagation: Niagahoster will display a message like "Awaiting External DNS." This is because it can take up to 24 hours for the domain to fully integrate with my website.
   ![Niagahoster awaiting external DNS page](/readme%20assets/Screenshot%202024-02-28%20221850.png)
4. Verification and completion: Once the process is complete, the Niagahoster DNS settings will show a checkmark next to the Netlify nameservers, indicating successful integration. Your website will then be accessible using your custom domain!
   ![Niagahoster Netlify DNS Completion](/readme%20assets/Screenshot%202024-02-28%20224000.png)

## Final Result

The final result of my website is now live at https://childrenofindonesia.site
![Children of Indonesia Webpage](/readme%20assets/Screenshot%202024-02-29%20at%2020-12-32%20Children%20of%20Indonesia.png)

## Acknowledgements

-   [GitHub Profile](https://github.com/anojumisa)
-   [LinkedIn](https://www.linkedin.com/in/anojumisa/)
