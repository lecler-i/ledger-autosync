### Fork of ledger-autosync

This is a fork of the project [ledger-autosync](https://gitlab.com/egh/ledger-autosync/-/tree/master) on gitlab.

My modifications include : 

 - Stripping of dates in the transaction detail
   - This is because my bank add the date in various transactions (ATM whitdraw ect) and I want the name to be always
       the same for `payee` automatching.
 - Make sure all whitespaces are stipped out of the description 
   - Same as the above, just to sanitize the names of the transactions coming from my bank exports
