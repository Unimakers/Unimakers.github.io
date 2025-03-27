---
layout: page
title: Install
description: >
  Recalbox est un système d'exploitation (OS) destiné à l'émulation de jeux vidéo rétro. Toutefois, il est important de noter que l'installation de Recalbox sur votre propre PC peut avoir des conséquences graves, potentiellement irréversibles si vous l'installer de la mauvaise façon.
accent_color: '#E04750'
accent_image:
  background: '#2D2D36'
  overlay:    false
---

**Recalbox** est un système d'exploitation open source spécialement conçu pour les amateurs de jeux vidéo rétro. Il offre une plateforme de jeu complète et conviviale pour émuler une grande variété de consoles et d'ordinateurs anciens, permettant aux utilisateurs de revivre les classiques du jeu vidéo directement sur leur matériel moderne.

Recalbox est doté de plein de qualité: 

**Émulation de consoles rétro** : Recalbox prend en charge l'émulation d'une large gamme de consoles de jeux rétro, notamment la NES, la SNES, la Sega Genesis, la PlayStation, la Game Boy, la Atari 2600, et bien d'autres. Il offre également une compatibilité avec un grand nombre de jeux, ce qui vous permet de jouer à vos titres préférés de l'ère rétro.

**Interface utilisateur conviviale** : L'interface de Recalbox est conçue pour être simple et intuitive. Les utilisateurs peuvent naviguer facilement dans leur collection de jeux, personnaliser les paramètres d'émulation et accéder à diverses fonctionnalités sans trop d'efforts.

**Configuration facile** : L'installation et la configuration de Recalbox sont relativement simples, ce qui en fait une option idéale pour les débutants en émulation. Il prend en charge une grande variété de contrôleurs USB et permet de configurer les boutons rapidement.

**Multijoueur local** : Recalbox prend en charge le multijoueur local, ce qui signifie que vous pouvez jouer à des jeux rétro classiques avec vos amis en utilisant des manettes et des écrans partagés.

**Personnalisation avancée** : Bien que Recalbox soit convivial pour les débutants, il offre également des options de personnalisation avancées pour les utilisateurs expérimentés. Vous pouvez ajuster les paramètres d'émulation, ajouter des thèmes personnalisés et même étendre la liste des émulateurs pris en charge.

**Mises à jour régulières** : La communauté de Recalbox est active et propose régulièrement des mises à jour, améliorations et corrections de bugs pour garantir une expérience de jeu optimale.

**Gratuit et open source** : En effet c'est un logiciel open source et qui dit open source dit **GRATUIT**, ce qui signifie qu'il est disponible gratuitement pour tous. Vous pouvez donc le télécharger, l'installer et le personnaliser selon vos besoins !!!

Je vous conseil tout de même de regarder cette video qui l'expliquera bien mieux que moi

<iframe width="800" height="600" src="https://www.youtube.com/embed/GoXhHcLyz58" title="BIEN COMMENCER AVEC RECALBOX EN MOINS DE 10MIN ! (SPECIAL DEBUTANTS!)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**NOTE** La suite arrive {:.message}


























<!--Buyers of the PRO version should [follow these steps](#pro-version).

## Table of Contents
{:.no_toc}
0. this unordered seed list will be replaced by toc as unordered list
{:toc}

## Via Starter Kit
Using the Starter Kit has the advantage of not cluttering your blog repository.
Additionally, it allows you to publish your site on GitHub Pages with a single `push`.

If you have a GitHub account, fork the [hydejack-starter-kit](https://github.com/qwtel/hydejack-starter-kit) repository.
Otherwise [download the source files](https://github.com/qwtel/hydejack-starter-kit/archive/master.zip)
and unzip them somewhere on your machine.

**NOTE**: In addition to the docs here, you can follow the quick start guide in the starter kit.
{:.message}

`cd` into the directory where `_config.yml` is located and follow the steps in [Running locally](#running-locally).

## Via gem
Jekyll has [built-in support](https://jekyllrb.com/docs/themes/) for using themes that are hosted on RubyGems.  

If you haven't already, create a new Jekyll site first:

~~~bash
$ jekyll new <PATH>
~~~

Your site's root dir should look something like this

~~~
├── _posts
│   └── 2017-04-07-welcome-to-jekyll.markdown
├── _config.yml
├── about.md
├── Gemfile
├── Gemfile.lock
└── index.md
~~~

**NOTE**: Hydejack works with Jekyll's default `config.yml`, but it is recommended that you replace it with
[Hydejack's default config file](https://github.com/qwtel/hydejack/blob/master/_config.yml).
It contains the names of all config options known to Hydejack and provides sensible defaults (like minifying HTML and CSS in production builds).
{:.message}

Next, you'll want to add `jekyll-theme-hydejack` as a dependency by adding the following line to the `Gemfile`.

~~~ruby
gem "jekyll-theme-hydejack"
~~~

(You can also remove the old theme `jekyll-theme-minima` from the Gemfile)

Now you want to edit the `_config.yml` of your Jekyll site and set Hydejack as the theme.
Look for the `theme` key and set its value to `jekyll-theme-hydejack`.

~~~yml
theme: jekyll-theme-hydejack
~~~

For more information on gem-based themes, see the [Jekyll Documentation](http://jekyllrb.com/docs/themes/).

You can now continue with [running locally](#running-locally).

## Via zip
If you downloaded the [extended zip](https://github.com/qwtel/hydejack/releases),
extract the contents somewhere on your machine.
The high-level folder structure will look something like.

~~~
├── _data
├── _featured_categories
├── _featured_tags
├── _includes
├── _js
├── _layouts
├── _posts
├── _sass
├── assets
├── _config.yml
├── 404.md
├── about.md
├── index.html
└── posts.md
~~~

`cd` into the directory where `_config.yml` is located and follow the steps in [Running locally](#running-locally).

## Via git
If you are familiar with using git, you can add the [Hydejack repository](https://github.com/qwtel/hydejack)
as a remote, and merge its master branch into your working branch.

~~~bash
$ git remote add hydejack git@github.com:qwtel/hydejack.git
$ git pull hydejack master
~~~

You can also update Hydejack this way. The master branch will not contain work in progress,
but will contain major (breaking) changes.
This approach is recommended if you intend to customize Hydejack.

You can now continue with [running locally](#running-locally).

## PRO Version
If you bought the PRO version, you've received a zip archive with the following contents:

~~~
├── install
├── upgrade
├── CHANGELOG _ Hydejack.pdf
├── Documentation _ Hydejack.pdf
├── NOTICE _ Hydejack.pdf
├── PRO License _ Hydejack.pdf
├── PRO–hy-drawer License _ Hydejack.pdf
├── PRO–hy-push-state License _ Hydejack.pdf
├── icon.psd
├── sidebar-bg.psd
├── *-to-v7.5.2.diff
└── .ssh
~~~

`install`
: Contains all files and folders needed to create a new blog.

`upgrade`
: Contains only the files and folders needed for upgrading form an earlier version of Hydejack (6.0.0 or above).
  See the [Upgrade]{:.heading.flip-title} for more.

`CHANGELOG _ Hydejack.pdf`
: The [changelog](../../CHANGELOG.md) in PDF form.

`Documentation _ Hydejack.pdf`
: This documentation in PDF form.

`NOTICE _ Hydejack.pdf`
: The [notice](../../NOTICE.md) in PDF form.

`PRO License _ Hydejack.pdf`
: The license for use of Hydejack PRO in PDF form.

`PRO–hy-drawer License _ Hydejack.pdf`
: A license for use of [hy-drawer](https://qwtel.com/hy-drawer/) as part of Hydejack PRO.

`PRO–hy-push-state License _ Hydejack.pdf`
: A license for use of [hy-push-state](https://qwtel.com/hy-push-state/) as part of Hydejack PRO.

`icon.psd`
: A Photoshop template to help with generating the favicon, apple touch icon, etc.

`sidebar-bg.psd`
: A Photoshop template for blurred sidebar backgrounds.

`*-to-v7.5.2.diff`
: There will be multiple fo these files, where `*` is a previous version.
  They are git patches that you can apply to your repository via [git-apply](https://git-scm.com/docs/git-apply).
  Use these if you are using git and you are worried about accidentally overwriting changes you've made to Hydejack PRO.
  This is for advanced users.

`.ssh`
: A hidden folder containing a SSH key for read-only access to the Hydejack PRO GitHub repository.
  You can use this to install Hydejack PRO as gem-based theme.
  See the [installation instructions](#pro-via-github-advanced) below.
  This is for advanced users.

For new installations only the `install` folder is interesting.
Unzip the archive somewhere on your machine, then `cd` *into* the `install` folder, e.g.

~~~bash
$ cd ~/Downloads/hydejack-pro-7.5.2/install/
~~~

You can now continue with [Running locally](#running-locally).

### PRO via GitHub (advanced)
If you know how to handle SSH keys, you can also install the PRO version as a gem-based theme via GitHub.
The advantage of this method is that you avoid cluttering your Jekyll repository with Hydejack's source files.

The downloaded zip contains a read-only key for a private GitHub repository.
It is located at `<dowloaded zip>/.ssh/hydejack_pro_customers`.
You have to copy the key file to `~/.ssh` (or wherever your SSH keys are located), e.g.:

~~~bash
$ cp ~/Downloads/hydejack-pro-v7.5.2/.ssh/hydejack_pro_customers ~/.ssh/
~~~

It is required that your private key files are NOT accessible by others, e.g.:

~~~bash
$ chmod 600 ~/.ssh/hydejack_pro_customers
~~~

Then add the following to `.ssh/config`:

~~~
Host hydejack
	HostName github.com
	IdentitiesOnly yes
	IdentityFile ~/.ssh/hydejack_pro_customers
~~~

Next, open `Gemfile` in your Jekyll repository and add:

~~~ruby
gem "jekyll-theme-hydejack-pro", git: 'git@hydejack:qwtel/hydejack-pro.git', branch: 'gem-pro'
~~~

In your `_config.yml`, add:

~~~yml
theme: jekyll-theme-hydejack-pro
~~~

You can now continue with [Running locally](#running-locally).

## Running locally
Make sure you've `cd`ed into the directory where `_config.yml` is located.
Before running for the first time, dependencies need to be fetched from [RubyGems](https://rubygems.org/):

~~~bash
$ bundle install
~~~

**NOTE**: If you are missing the `bundle` command, you can install Bundler by running `gem install bundler`.
{:.message}

Now you can run Jekyll on your local machine:

~~~bash
$ bundle exec jekyll serve
~~~

and point your browser to <http://localhost:4000> to see Hydejack in action.


Continue with [Config](config.md){:.heading.flip-title}
{:.read-more}


[upgrade]: upgrade.md
[v5to6]: upgrade.md#from-hydejack-v5
[v6to6]: upgrade.md#from-hydejack-v6
-->