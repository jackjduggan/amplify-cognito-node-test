# amplify-cognito-node-test

Things I did

npm install -g @aws-amplify/cli

npx create-react-app amplify-cognito-node

In my AWS account, I created a new user, and gave them administrator-access-amplify permissions. I then created access keys for the new user.

amplify configure

Add the user details

amplify init

Everything should work successfully - if not, try making another user and giving full administrator access, not just amplify.
If everything worked successfully, you should see an "amplify" directory appear, and a file called src/aws-exports.js

amplify add auth

Select default configuration, then email, then done (for this test only)

amplify push

After a few mins, should see "deployment state saved succesfully".