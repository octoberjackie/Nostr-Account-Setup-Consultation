# Nostr Account Setup Consultation - 25k Sats Bounty

Looking for expert guidance from **Turi$mo** on setting up and optimizing my Nostr presence. This consultation is worth **25,000 sats** for comprehensive answers to the following questions.

## Account Discovery & Visibility

- [x] **Hashtag Strategy**: What hashtags do you recommend for bounty discoverability on Nostr?

#bountystr #bounty #bounties are quite popular for posting bounties on nostr. with a proper description of the task, what needs to be delevered, plus the rewards

- [x] **Cross-Platform Integration**: Is cross-posting from X (Twitter) to Nostr possible and advisable?

currently most cross-posting platforms are still in work. there is openVibe - client both Android & iOS that supports cross-platform posting across the following
- nostr
- bluesky
- mastadon
- threads [recently added]

- [x] **Verification & Visibility**: Do I need NIP-05 verification to be more visible? How important is getting verified?

NIP-05 verification is important for Web of Trust, most relays if not most implement this as a filter.
Secondly, it is a reference to your domain, and a means for users to verify you are who who are, and from the specific organization that you claim.
To verify your publickeys, you add them to the /.well-known/nostr.json for your domain
  - include the list of user in the organization


## Profile Management & Client Strategy

- [x] **Multi-Profile Setup**: Is it a good idea to use 2 profiles on 1 Nostr app (like LB and personal accounts on Primal)?

Yes, it is recommended to use separated accounts for both personal and business. To separate and curate your accounts accordingly.

- [x] **Dedicated Clients**: Or would it be better to use dedicated clients for each profile (personal on Primal, LB on Amethyst)?

This is a personal preference. There are clients that right now support multiple accounts set-up. One can choose to use their favorite client with multiple accounts for consistency

- [x] **Profile Key Issue**: Why do I have the same Nostr verified address but different profiles/public keys?

Your Nostr account has :
1.) publickey - hex format
2.) npub - bech32 format [converted from the hex format]


## Technical Configuration

- [x] **Relay Recommendations**: What relays would you recommend for discovery on Nostr?

Web of Trust relays. Free or Paid relays.

- [x] **Relay Connection Issues**: LB Nostr relays aren't showing up, even after resetting to default. Any thoughts on why this might be happening?

Perhaps a client side issue? would need more details to give a more informed response


## Multi-User Wallet Setup

- [x] **Shared Wallet Management**: What are your suggestions for setting up a Nostr wallet on Primal when multiple users control the LB Nostr account across different devices?

Nostr Wallet Connect with multiple strings would be ideal. Set spedn limits on the wallets. NB this is for sending payments.
For receiving you can only set up one address per nostr account, no matter how many clients you run the account on.


---

**Payment**: 25,000 sats upon completion of comprehensive consultation. I'll post this on app.lightningbounties.com. Just x the boxes, or drop an answer below then send in PR with close keyword. 

See here for detailed instructions -> 
https://docs.lightningbounties.com/docs/getting-started/solving-a-bounty/working-on-the-bounty
