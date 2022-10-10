
# Table of Contents

1.  [SoftwareX org-mode template](#org1a1215f)


<a id="org1a1215f"></a>

# SoftwareX org-mode template

`SoftwareX_article_org_template` is a org-mode template file for writing articles
based on Elsevier's SoftwareX latex template.

You only have to open it in Emacs and export with the org-mode latex exporter,
usually typing `C-c C-e l p` for tex and pdf file generation.

Note that some section headers are hidden. This behavior is achieved thanks to
the `ignore` tag. To make it work, add the following to your emacs setup (`init.el`
or in the `user-config` function of your `.spacemacs`):

    (require 'ox-extra)
    (ox-extras-activate '(ignore-headlines)) 

Please note that my own .spacemacs is included in this repository for reference.

