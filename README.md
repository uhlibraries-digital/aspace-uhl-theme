# ArchivesSpace UHL Public User Interface Theme

University of Houston Libraries Branding and Welcome text for [ArchivesSpace](https://github.com/archivesspace/archivesspace)

## Install

This theme is a ArchivesSpace plugin. Please make backups of all your plugins before installing. It is assumed you have the latest version of ArchivesSpace already installed.

Installation:

1) Download the UHL public theme

```
$ cd /path/to/archivesspace/plugins
$ git clone https://github.com/uhlibraries-digital/aspace-uhl-theme.git uhl-theme
```

2) Update ArchivesSpace `config/config.rb` and add `uhl-theme` to `AppConfig[:plugins]`. You might have to uncomment this line (remove `#`) if this is the first time installing a plugin. [Read more](http://archivesspace.github.io/archivesspace/user/archivesspace-plug-ins-readme/) about ArchivesSpace Plugin-ins.

```
AppConfig[:plugins] = ['uhl-theme']
```

3) Restart ArchivesSpace

## Development

Information on making changes to the ArchivesSpace theme is at https://github.com/archivesspace/archivesspace/blob/master/CUSTOMIZING_THEMING.md.

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or other method with the Digital Asset Management Team before making a change.

### Pull Request Process

1) Fork this repository before making any changes
2) Ensure you have pulled changes from this repository, or upsteam, if you have previously forked this repository
3) Ensure that any local development dependencies are removed
4) Make a pull request to this repository
5) Notify the Digital Asset Management Team a pull request was made with the change