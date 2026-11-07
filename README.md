# Rubbl Agent Skills

[![skills.sh](https://skills.sh/b/rubbl-platform/agent-skills)](https://skills.sh/rubbl-platform/agent-skills)

Agent skills for finding heavy equipment and construction attachments on [Rubbl](https://www.rubbl.com/).

## Install

```bash
npx skills add rubbl-platform/agent-skills
```

Install just the equipment-search skill:

```bash
npx skills add rubbl-platform/agent-skills --skill rubbl-equipment-search
```

The skills CLI supports Codex, Claude Code, Cursor, and other compatible agents. Select your agent during installation.

## Equipment search

[rubbl-equipment-search](skills/rubbl-equipment-search/SKILL.md) teaches an agent to search Rubbl's public marketplace, compare relevant listings, and link users directly to rentals, used equipment, and attachments.

Example prompts:

- Find a skid steer rental near Dallas for a week and compare advertised rates.
- Find a telehandler near Phoenix with the lift height and capacity I need.
- Compare excavators for sale on Rubbl with published prices and operating hours.
- Find a tooth bucket for my Bobcat T770 and identify any fitment questions.

The skill uses public web pages through your agent's browsing tools. No Rubbl API key or account is required to browse. It does not include a developer API, internal operations tooling, or access to customer records. Listings and advertised prices are subject to current availability and terms; bookings, purchases, and inquiries require the user's direction.

## Links

- [Rubbl](https://www.rubbl.com/)
- [Equipment rentals](https://www.rubbl.com/equipment-rentals/all)
- [Equipment for sale](https://www.rubbl.com/equipment-for-sale/all?radius=anywhere)
- [Attachments](https://www.rubbl.com/shop/attachments)
- [Contact Rubbl](https://www.rubbl.com/contact)
- [Skills directory](https://skills.sh/rubbl-platform/agent-skills/rubbl-equipment-search)

## License

MIT. See [LICENSE](LICENSE).
