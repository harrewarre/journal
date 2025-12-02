#itq #vpn
We currently have an organization on [https://github.com/orangeglasses](https://github.com/orangeglasses), which (to my knowledge) is only used to store code. This makes it quite a costly solution (the org is not free) for which we have a much better alternative!

MSP has been working behind the scenes to enable access to our very own internally hosted Gitlab instance. Gitlab is already used by MSP for various tasks so making use of an already existing solution instead of paying (Value4Money) for an additional one makes sense.

**So how does this work?** The MSP team has enabled the access through Workspace One so you should be able to connect to it on this address: [https://gitlab.msp.itq.eu](https://gitlab.msp.itq.eu) if you are properly enrolled. From there you'll assigned a team (in the Cloud native case, the Cloud native team 😉) and you should be able to create repositories, pipelines and all that goodness in the Cloud Native group on Gitlab.

**But I'm using Linux!** We've got that solved as well. You can request a profile here [https://itq.openvpn.com/](https://itq.workvivo.com/linkshim?l=https%3A%2F%2Fitq.openvpn.com%2F&i=eyJpdiI6IkV3T2JZRjJPYVppYWs5eVF6eXcwWnc9PSIsInZhbHVlIjoibGZxdTFUR2ErUGNxZ1BmRmdXWUE4QT09IiwibWFjIjoiMzM1NDdkZjNjMWQyNzdkMDJmY2FmZmQzODVmZGFhMTg2NGZjYmQyZmIwODI5NTg1NTk5ZjNmNmRkNjg3M2M1NCIsInRhZyI6IiJ9) and use the openvpn3 client to connect yourself to the ITQ network. Once connected you can start using Gitlab.

**But I'm using Github to share code with my customer!** That sounds a bit like an ownership issue. Code owned by our customers should be hosted at our customers. You can use Gitlab for this but then your customer can not access the code without you.

**So what should you do?**

- Go to our own Gitlab instance and register an SSH key or token so that you can start accessing Gitlab using tools like git.
- Go to the orange glasses Github org and have a look at the code that you work(ed) on.
- If the code is valuable, move it to a new repo on Gitlab.
- If the code is NOT valuable, make a note of the repo.
- Once you've checked all the code you own, send the list of obsolete repos to [Sander Harrewijnen](https://itq.workvivo.com/directory/people/3007248) so they can be deleted.
- If at that point you no longer need access to Github, mention that as well so we can remove your account from the org.

Review the git docs for help moving from one remote to another: [https://git-scm.com/docs/git-remote](https://git-scm.com/docs/git-remote)

If you need help with anything on Gitlab, [Sander Harrewijnen](https://itq.workvivo.com/directory/people/3007248) is the owner of the Cloud Native group.

Anything left over after May 5th will end up abandoned because we will start removing users from Github. The next payment for Github is scheduled for May 20th, so we have until then to get everything (we want to keep) moved over.

Some handy links:

- Gitlab: [https://gitlab.msp.itq.eu](https://gitlab.msp.itq.eu)
- Github: [https://github.com/orangeglasses](https://github.com/orangeglasses)
- VPN profiles: [https://itq.openvpn.com/](https://itq.openvpn.com/)
- Openvpn3: [https://community.openvpn.net/openvpn/wiki/OpenVPN3Linux](https://community.openvpn.net/openvpn/wiki/OpenVPN3Linux)

If you need some help with anything, contact [Sander Böhm](https://itq.workvivo.com/directory/people/3035727) or [Sander Harrewijnen](https://itq.workvivo.com/directory/people/3007248)