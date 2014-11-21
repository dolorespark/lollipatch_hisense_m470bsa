lollipatch_hisense_m470bsa
===============================

This repo contains patches needed to build AOSP using Hisense's proprietary blobs. It's layout parallels that of the individual git repos in the AOSP tree. Except for the '.repo' subtree, each patch can be applied directly to the corresponding repo.

Under '.repo/local_manifests' you'll find my raw 'local_manifest.xml' file (i.e. not a patch). Put it in the corresponding directory in your AOSP tree to pull in the other repos this ROM uses.

Note: 'Philz Touch Recovery' does not (yet) build using AOSP 5.0 (but will eventually). Be sure that RECOVERY_VARIANT (if present) is not set in your 'BoardConfig.mk'.
