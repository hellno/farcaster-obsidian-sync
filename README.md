# Farcaster Obsidian sync plugin

3. Fill in a URL to your repository. You can replace with `https://github.com/nolebase/obsidian-plugin-template`
4. Fill in the Why, Features, What can you do with it, Demos, How to install, TODOs, feel free to remove the sections that are not needed.
5. Replace the name `SomeViewPlugin` and `SomePlugin` with your own plugin name.

## ⚠️ How to publish?

1. Modify the version in the `manifest.json` file.
2. Modify the version in the `package.json` file.
3. Push the changes to the repository.
4. Go to the [Release] page of the repository.
5. Create a new release with the tag name as the version number.
6. Sit back and relax, the plugin will be published with CI/CD pipelines automatically.

## 🤔 Why

Do you want to keep a local copy of your activity on Farcaster? This plugin will help you sync your Farcaster activity to your Obsidian vault.

## 🎨 Features

- 📦 Out of the box support.
- 🚀 Blazingly fast.
- 💡 You define it.

## 📺 Demos

> Show me what you can do

### How it looks like

Perhaps a GIF?

## 😎 How to install

### Install with beta testing helper [BRAT](https://tfthacker.com/brat-quick-guide) plugin

1. Install the [BRAT](https://tfthacker.com/brat-quick-guide) plugin right from the official Obsidian plugin store.
2. Enable the BRAT plugin in the community plugins settings menu.
3. Open Command palette to choose `BRAT: Plugins: Add a beta plugin for testing`.
4. Copy and paste the following link to the first field of the new prompted dialog:

```txt
https://github.com/nolebase/obsidian-plugin-template
```

5. Find the needed released version on [Release page of Obsidian UnoCSS Plugin](https://github.com/nolebase/obsidian-plugin-template/releases), for example, fill in `0.1.0`.
6. Enable the "Obsidian Template Plugin" plugin from the `Installed plugins` list.

### Install manually

1. Navigate to the [Release page of Obsidian Template Plugin](https://github.com/nolebase/obsidian-plugin-template/releases)
2. Find the [latest version of the plugin](https://github.com/nolebase/obsidian-plugin-template/releases/latest).
3. Download the `main.js` file and `manifest.json` file.
4. Open up the `.obsidian/plugins` directory of your Obsidian vault.
5. If no `.obsidian/plugins` directory exists, create one.
6. Create a new directory named `obsidian-plugin-template` inside the `.obsidian/plugins` directory.
7. Move `main.js` file and `manifest.json` file into the `obsidian-plugin-template` directory.

The directory structure should look like this after these steps:

```shell
❯ tree
.
├── main.js
├── manifest.json
```

8. Enable the "Obsidian Template Plugin" plugin from the "Installed plugins" list.

## ⏳ TODOs

- [ ] Anything on the roadmap?

## 💻 How to develop

1. As [Build a plugin - Developer Documentation](https://docs.obsidian.md/Plugins/Getting+started/Build+a+plugin) has suggested, create a separate vault for development.
2. (Optional) Install the hot-reload plugin: [pjeby/hot-reload](https://github.com/pjeby/hot-reload).
3. Create a `.obsidian/plugins` directory in the vault root.
4. Clone this repository into the `.obsidian/plugins` directory.
5. Install dependencies

```shell
pnpm install
```

If you use [`@antfu/ni`](https://github.com/antfu/ni), you can also use the following command:

```shell
ni
```

6. Build the plugin for development

```shell
pnpm run build:dev
```

If you use [`@antfu/ni`](https://github.com/antfu/ni), you can also use the following command:

```shell
nr build
```

7. Reload Obsidian to see the changes. (If you use the hot-reload plugin, you don't need to reload Obsidian manually.)

> Reloading can be called from the command palette with `Reload app without saving` command.

## 🔨 How to build

```shell
pnpm run build
```

If you use [`@antfu/ni`](https://github.com/antfu/ni), you can also use the following command:

```shell
nr build
```

Made with ♥ on Farcaster

