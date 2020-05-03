You may access this page by swiping from the right hand side of your screen to open the side bar menu. The hamburger menu (three horizontal bars) will also open this menu if you are on a page with that option.

## Getting Started
You can get stated with this workflow by picking a scanning mode at the bottom of the screen.

### Rapid Scan
Allows you to scan many items without leaving the scanning screen. This is makes workflows involving multiple items more efficient since there is no a camera-start-up time between scans.

### Scan Item
For scanning only a single item. After your item is scanned you will be returned to the list of scan results.

## Scan workflow
As you scan items the results will be read to you by your phone's text to speech engine. PantryParty will only read the first scan of a barcode to you. Subsequent scans which match an already scanned barcode are not read.

If you receive a notification that an item was scanned, and the lookup failed or the lookup produce incorrect results you should exit the scanner and correct the error.

## Scan Results
This view is filled with all of the items you have scanned.

The view includes:

* An Icon representing the status of the scan result
* The name that was found in Grocy or derived from a barcode source
* The quantity of the scanned item

### Status Icons

|  Icon  | Meaning |
| :----: | :-----: |
| ![Warning Icon](./assets/scanned_item_status_warning.png) | A warning icon indicates that attention is required to save this item. This is usually a missing Grocy Product |
| ![Pending Icon](./assets/scanned_item_status_pending.png) | This icon indicated the save of your changes is pending. Every time you modify the item the save countdown is restarted. |
| ![Saved Icon](./assets/scanned_item_status_saved.png) | Your changes have been successfuly saved |

## Product Creation
As you have been scanning the app a has been saving your changes to Grocy, if more than 20 second has elapsed. However any items which lack a product will not have been saved.

You can quickly tell how many items you have scanned which lack a product by the presence of this yellow bar.

![Product Quick Create Entry](./assets/product_quick_create_entry.png)

Tapping this bar will drop you into a [guided process to create all missing products](./product-quick-create).

## Removing A Scan Result
Occasionally you will scan an item and the barcode is read wrong by you phone's built-in systems. In this case your best course of action is to simply remove the incorrect scan results.

Any scan results can be removed by taping the item, and selecting the trash can in the top right of your screen.

## Editing a Scan Result

By default most scans you make do not require manual intervention, however sometimes editing them by hand is the best course of action.

Editing a scanned item manually allows you to:

* Increment or decrements the quantity, without scanning subsequent items
* Change the location from the Product's default
* Change, or set the product to an existing Grocy product

You may edit a scanned item by tapping on it's entry. Editing items which have already been saved will undo most of the changes, and re-save the item.

