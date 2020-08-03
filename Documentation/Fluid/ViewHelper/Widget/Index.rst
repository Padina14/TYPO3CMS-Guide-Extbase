.. include:: ../../../Includes.txt

ViewHelper: Widgets
===================
Custom Templates in plugins
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Define your custom template `Index.html` in `EXT:my_extension/Resources/Private/Templates/Viewhelpers/Widget/Paginate`. Define in the typoScript of the extension :
:: 

   plugin.tx_myExtension {
    view {
        templateRootPaths.0 = EXT:my_extension/Resources/Private/Templates/
        widget {
            TYPO3\CMS\Fluid\ViewHelpers\Widget\PaginateViewHelper {
                templateRootPaths.10 = EXT:my_extension/Resources/Private/Templates/
            }
        }
    }


**Table of Contents**

.. toctree::
   :maxdepth: 5
   :titlesonly:
   :glob:

   Autocomplete
   Link
   Paginate
   Uri
