Continuous Deployment with AWS Code Pipeline and S3

Summary
Host the game code on GitHub. Create an S3 bucket for static website hosting and set up a continuous deployment pipeline using AWS Code Pipeline to automatically deploy the code whenever changes are detected.

The Game
A basic memory matching game where the user clicks two cards (featuring meme images) to find pairs. If a match is found, the cards are removed from the board. If not, they flip back to their blank sides, allowing the user to try again.

The game is built using HTML, CSS, and JavaScript.

Possible additional features:

- A scoring system
- A timer
- More cards
- Multiplayer capabilities for score comparison
- Deployment Environment
- The code will be hosted and deployed in an S3 bucket.

Deployment Pipeline
Using AWS Code Pipeline, create a pipeline that retrieves the code from GitHub and deploys it to S3 whenever there is a code change.

Costs
All services mentioned are part of the AWS Free Tier. However, costs may incur eventually, so it's advisable to shut down resources once this tutorial is completed.
