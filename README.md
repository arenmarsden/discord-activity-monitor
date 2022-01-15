**Original Project: [brhigginsuk/discord-activity-monitor](https://github.com/brhigginsuk/discord-activity-monitor)**

**SECURITY NOTICE: THIS BRANCH IS VULNERABLE TO SEVERAL UNRESOLVABLE PROTOTYPE POLLUTION AND COMMAND INJECTION VULNERABILITIES. 
MYSELF, NOR THE ORIGINAL CREATOR TAKE RESPONSIBILITY IF YOU DECIDE TO USE AN INSECURE VERSION OF THIS PROJECT.**

I am in the process of recoding this bot to ensure security, so please be patient, and if you need to use it, run it inside an isolated container.

# Discord Activity Monitor
A Discord bot to assign/remove a role from users in your guild based on whether they have been active lately.

## Features
- Remove an 'active' role from a user who has not been active for a number of days
- Optionally assign an 'inactive' role to a user when they lose the 'active' role
- Optionally re-assign the 'active' role when a user who becomes active again
- Configure specific users or roles to be exempt from monitoring
- Configure threshold for inactivity

## Use cases
- Keep active members at the top of the members sidebar
- Reward active members for participating in the community
- Recognise how many inactive members your server has

## Permissions

The bot requires certain permissions, which you are prompted for on the invite screen.
Each permission has a reason for being required, explained below.

| Permission    | Reason                                       |
| ------------- | -------------------------------------------- |
| Read messages | Detect when people are active                |
| Send messages | Ask setup questions and respond to commands  |
| Manage roles  | Assign and remove the active role from users |
| Embed links   | Respond to commands                          |

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
