<p align="center">
  <img src="https://cl.ly/qurB/greyicon.png" height="64">
  <h3 align="center">Vend</h3>
  <p align="center">A CLI tool to interact with the Vend API.<p></p>


## Commands

- Export Sales Ledger
- Export Customers
- Export Gift Cards
- Export Store Credits
- Export Images
- Import Images
- Import Store Credits
- Import Suppliers
- Void Gift Cards 

## Usage Examples

When running a command you need to pass the flags that specify the parameters for that tool. There are two sets of flags, global flags and command flags. Global flags such as domain prefix and token are required on all commands and command flags are passed depending on the tool. 

#### Export Sales Ledger

	$ vend export-sales -d domainprefix -t token -z timezone -F 2018-03-01 -T 2018-04-01 -o outletname

#### Export Customers

	$ vend export-customers -d domainprefix -t token

#### Export Gift Cards

	$ vend export-giftcards -d domainprefix -t token

#### Export Store Credits

	$ vend export-storecredits -d domainprefix -t token

#### Export Images

	$ vend export-images -d domainprefix -t token

#### Import Images

	$ vend import-images -d domainprefix -t token -f filename.csv

#### Import Store Credits

	$ vend import-storecredits -d domainprefix -t token -f filename.csv

#### Import Suppliers

	$ vend import-suppliers -d domainprefix -t token -f filename.csv

#### Void Gift Cards

	$ vend void-giftcards -d domainprefix -t token -f filename.csv

## Need Help?

If you are unsure which flags are needed for the command just type the command followed by --help, which will show you a breakdown of the required flags and a download link if a template file is needed.

	$ vend command-name --help

## Related Repositories

- [GoVend](https://github.com/jackharrisonsherlock/govend)

## Disclaimer

This is by no means endorsed by Vend, and is a library built for Vend's experimental 2.x API so should be used with caution.