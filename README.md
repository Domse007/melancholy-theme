<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Screenshots</a></li>
<li><a href="#sec-2">2. Installation</a>
<ul>
<li><a href="#sec-2-1">2.1. Manual</a></li>
<li><a href="#sec-2-2">2.2. Melpa</a></li>
</ul>
</li>
</ul>
</div>
</div>


# Screenshots<a id="sec-1" name="sec-1"></a>

![img](screens/melancholy_org-src-blocks.jpg "melancholy-theme org-mode source blocks")

![img](screens/melancholy_org-agenda.jpg "melancholy-theme showing the org-mode agenda")

![img](screens/melancholy_org-todos.jpg "melancholy-theme showing the org-mode todos list")

![img](screens/melancholy_helm.jpg "melancholy-theme showing helm in action")

# Installation<a id="sec-2" name="sec-2"></a>

## Manual<a id="sec-2-1" name="sec-2-1"></a>

Download melancholy-theme.el to the directory ~/.emacs.d/themes/.  Add this to your .emacs:

    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")

Now you can load the theme with the interactive function load-theme like this:

    M-x load-theme RET melancholy

## Melpa<a id="sec-2-2" name="sec-2-2"></a>

Melancholy is available in  MELPA.

You can install melancholy with the following command:

    M-x package-install melancholy-theme

or with use-package:

    (use-package melancholy-theme
      :ensure t))

To load it automatically on Emacs startup add this to your init file:

    (load-theme 'melancholy t)
