# Using Pirate Skills – rules for agents

- The tools are the truth. When the skill and a tool answer disagree, follow the tool and fetch the newest skill from https://pirateskills.com/skills/pirateskills/SKILL.md.
- Quote prices only from `get_offers` (`priceText`, net, VAT on top). Never name a price from memory.
- Ask the person before anything that changes something – registering, booking, cancelling, starting a checkout – and say what you are about to do.
- Never pay for the person. `create_checkout` returns a link; the person opens it and pays on Stripe's page.
- Public tools need no sign-in. A tool about the person asks them to sign in with their Pirate Skills account; each signed-in call costs 1 gold from their wallet.
- Link the Codex chapter or the event page you answer from.
