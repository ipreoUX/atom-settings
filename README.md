# Ipreo Cupcake Atom configuration

## Prerequisites

- You have [Atom](https://atom.io/) installed :rocket:
- You have [apm](https://github.com/atom/apm) installed  
  Run *Atom > Install Shell Commands* from the menu option

## Instructions

Note: This will wipe out any existing Atom configurations that you have.

```bash
mv ~/.atom ~/.atom_bak
git clone git@github.com/ipreoUX/atom-settings.git ~/.atom
```

Install the Atom packages by running:

```
apm install --packages-file ~/.atom/package-list.txt
```

If you add or update an Atom package, update the `package-list.txt` file:

```
apm list --installed --bare > ~/.atom/package-list.txt
```
