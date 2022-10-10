
# SoftwareX org-mode template

`SoftwareX_article_org_template` is an org-mode template file for writing articles
based on Elsevier's SoftwareX latex template.

You just have to open it in Emacs and export it with the latex exporter in org
mode, usually typing `C-c C-e l p` for the generation of tex and pdf files.

Please note that some section headers are hidden. This behavior is achieved
thanks to the `ignore` tag. To make it work, add the following to your emacs
configuration (`init.el` or the `user-config` function of your `.spacemacs`):

    (require 'ox-extra)
    (ox-extras-activate '(ignore-headlines))

