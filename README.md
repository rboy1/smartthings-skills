<div align="center">
  <h1>SmartThings Skills</h1>
  <p>Agent skills for the SmartThings ecosystem.</p>
  <p>
    <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-green.svg" />
    <img alt="License: Apache-2.0" src="https://img.shields.io/badge/license-Apache--2.0-green.svg" />
    <a href="https://paypal.me/stephenmendez401" target="_blank">
      <img src="https://www.paypalobjects.com/webstatic/en_US/i/buttons/PP_logo_h_100x26.png" alt="PayPal" />
    </a>
  </p>
</div>

A collection of agent skills for working with the SmartThings ecosystem: Public API, CLI, Edge drivers, and SmartApps. These skills are designed to keep guidance grounded in official SmartThings documentation while staying concise and task-focused.

This is an unofficial community project and is not affiliated with SmartThings. Results may vary.

## Included Skills
- `smartthings-api`: SmartThings Public REST API and automations (rules, scenes)
- `smartthings-cli`: SmartThings CLI workflows
- `smartthings-edge-driver`: Edge device drivers (Lua) and protocol references
- `smartthings-smartapps`: SmartApps (Connected Services) lifecycle and hosting

## Repository Layout
- `skills/`: Skill folders, each with `SKILL.md` and optional `references/` files

## Usage
If you have an agent skills loader (e.g., Skills CLI), you can install a skill by referencing this repo path and skill folder.

Example (Skills CLI):
```bash
npx skills add 401unauthorized/smartthings-skills --path skills/smartthings-api
```

To pin to a specific release or commit, add a ref:
```bash
npx skills add 401unauthorized/smartthings-skills@v0.1.0 --path skills/smartthings-api
```

## Author
**Stephen Mendez**

- Website: https://www.stephenmendez.dev
- Github: [@401unauthorized](https://github.com/401unauthorized)

## Contributing
Contributions, issues and feature requests are welcome. Feel free to check the [issues page](https://github.com/401unauthorized/smartthings-skills/issues). You can also take a look at the [contributing guide](https://github.com/401unauthorized/smartthings-skills/blob/main/CONTRIBUTING.md).

## Show Your Support
Give a star if this project helped you.

Consider making a donation of any amount.

<a href="https://paypal.me/stephenmendez401" target="_blank">
    <img src="https://www.paypalobjects.com/webstatic/en_US/i/buttons/PP_logo_h_200x51.png" alt="PayPal" />
</a>

## License
Copyright © 2026 Stephen Mendez  
This project is [Apache-2.0](https://github.com/401unauthorized/smartthings-skills/blob/main/LICENSE) licensed.

---
SmartThings is a registered trademark of SmartThings, Inc.

Samsung is a registered trademark of Samsung Electronics Co., Ltd.
