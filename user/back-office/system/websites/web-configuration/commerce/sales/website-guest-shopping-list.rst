:oro_documentation_types: OroCommerce

.. _user-guide--system-configuration--commerce-sales-shopping-list-per-website:
.. _user-guide--system-configuration--commerce-sales-shopping-list--mass-action--website:

Configure Shopping List Settings per Website
============================================

In the Shopping List section of Commerce configuration settings, you can control the shopping list limit, guest shopping lists and their owners and mass product actions.

To configure them per website:

1. Navigate to **System > Websites** in the main menu.
2. For the necessary website, hover over the |IcMore| **More Options** menu to the right of the necessary website and click |IcConfig| to start editing the configuration.
3. Select **Commerce > Sales > Shopping List** in the menu on the left.

.. note::
   For faster navigation between the configuration menu sections, use :ref:`Quick Search <user-guide--system-configuration--quick-search>`.

  .. image:: /user/img/system/websites/web_configuration/ShopListWebsite.png

4. Clear the **Use Organization** check box to change the organization-wide setting.
5. In the **Shopping List Limit** section, set the number of shopping lists allowed per customer. The default value is zero. This means that no limit of shopping lists is applied.
6. In the **Guest Shopping List** section, set whether guests are allowed to create and manage shopping lists. Disabled by default.

   To enable guest shopping lists select the *Enable Guest Shopping List* check box.

7. In the **Guest Shopping List Owner Settings** section, select the user who will be the default owner of all guest shopping lists. Depending on the roles and permissions of the owner, guest shopping lists may or may not be viewed and managed by the users who are subordinated to the owner.

   .. note::  To enable users from the same business unit or organization (that the owner belongs to) to view and manage guest shopping lists, adjust permissions for the shopping list entity in their roles accordingly.

8. In the **Shopping List Options** section, set whether customer users are allowed to mass select and add items to the shopping list. Enabled by default.

   To disable them, clear the *Use Organization* and the *Enable Mass Adding on Product Listing* check boxes.

9. Click **Save Settings**.

.. finish

.. include:: /include/include-images.rst
   :start-after: begin

