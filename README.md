# MagTOCdata
This repository maintains the CSV files that are used by contributor users
of the MagTOCspotter app to locate and 'spot' the TOC pages in the Computer
Magazine Archives at the Internet Archive. It also maintains an optional
directory of copies of the JPG images of these TOC pages.

## NOTE: Ready and Not Ready for Prime Time
If used as is, this repo can be cloned locally and then its `tocdata`
directory can be copied into a local clone of the MagTOCspotter app as part
of the *MagTOCml* project. In this use case, your local app installation will
have its `tocdata` subdirectory overwritten with the state of the when-cloned
`MagTOCdata` repository. At initial commit, this means you will be working with
an app state where 430 TOC pages have been spotted in 377 computer magazine
issues in the collections of the Internet Archive.

In this use case state, you can spot TOC pages and locally register their
`item_id` and `leaf` number (roughly equal to the print page number). And,
depending on your app configuration in the app `ini` settings file, you may
also be capturing a local copy of a JPG image file of the TOC pages you spot.

As long as you don't overwrite your TOCspotter app with the state of then
MagTOCdata repo, you will be gathering good data that can _eventually_
contributed to the *MagTOCml* project. In the worst case, you and another
contributor _might_ spot the same TOC in the same issue of a magazine because
we don't have a process for real-time updating of the CSV files which
maintain the registry of done issues and spotted TOC page leaf IDs.

This aspect of the MagTOCml project community workflow is under development.

We will update this README and other documentation resources when this
workflow is in place.
