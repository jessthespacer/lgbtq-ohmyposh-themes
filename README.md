# LGBTQ+ terminal themes for Oh My Posh 🏳️‍🌈 💻

This repository contains themes for your terminal utilizing the colors in the various pride flags, applied through the power of the [Oh My Posh](https://ohmyposh.dev/) 👩‍💻 plugin by [Jan De Dobbeleer](https://github.com/sponsors/JanDeDobbeleer) [*et al.*](https://ohmyposh.dev/docs/contributors). Derived from the [`unicorn` 🦄 theme](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/unicorn.omp.json).

![Trans console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/sample-session.png)

## Installing Oh My Posh and Nerd Fonts

To install Oh My Posh, follow the instructions in its documentation 📝, available online:

- [Windows 🪟](https://ohmyposh.dev/docs/installation/windows)
- [macOS 🍏](https://ohmyposh.dev/docs/installation/macos)
- [Linux 🐧](https://ohmyposh.dev/docs/installation/linux)

**Please note that these themes require [Nerd Fonts](https://www.nerdfonts.com/) to work properly 🤓!** You can use Oh My Posh to install the Nerd Font of your choice (I recommend `CaskaydiaCove`) using the instructions [here](https://ohmyposh.dev/docs/installation/fonts).

Once Oh My Posh is installed, clone this repository to the directory of your choice, then follow the instructions [here](https://ohmyposh.dev/docs/installation/customize) to point Oh My Posh to your theme file of choice.

Browse Oh My Posh's built-in themes [here](https://ohmyposh.dev/docs/themes).

## Theme Setup Example

For example, to set up PowerShell ⚡ to use the trans theme 🏳️‍⚧️, first install Oh My Posh and a Nerd Font of your choice.

Then, navigate to your home directory 🏠 and clone this repository:

```pwsh
cd ~
git clone "https://github.com/jessthespacer/lgbtq-ohmyposh-themes.git"
```

Or alternatively, using the [GitHub CLI](https://cli.github.com/):

```pwsh
cd ~
gh repo clone jessthespacer/lgbtq-ohmyposh-themes
```

Find the location of your PowerShell configuration file by running the following command:

```pwsh
$PROFILE
```

Using the text editor of your choice, edit that file by adding the following line to it. This will set up Oh My Posh to use the trans theme 🏳️‍⚧️:

```pwsh
oh-my-posh init pwsh --config "~\lgbtq-ohmyposh-themes\trans.omp.json" | Invoke-Expression
```

Finally, refresh your terminal to load the theme 🎉:

```pwsh
. $PROFILE
```

## Theme Previews

Suggestions for changes and additions are welcome 💃! Please note that the glyph representing the laptop icon 💻 does not render correctly in these previews due to [renderer limitations](https://ohmyposh.dev/docs/share) but should render in your terminal as long as Nerd Fonts are set up correctly.

Root privileges are indicated by a 💅 glyph in front of the shell glyph.

### Asexual

![Asexual console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/asexual.png)

### Bisexual

![Bisexual console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/bisexual.png)

### Gay men

![Gay men console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/gay.png)

### Genderqueer

![Genderqueer console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/genderqueer.png)

### Intersex

![Intersex console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/intersex.png)

### Lesbian

![Lesbian console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/lesbian.png)

### Nonbinary

![Nonbinary console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/nonbinary.png)

### Pansexual

![Pansexual console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/pansexual.png)

### Trans

![Trans console theme](https://raw.githubusercontent.com/jessthespacer/lgbtq-ohmyposh-themes/main/sample-images/trans.png)