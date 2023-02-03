template-package
================

An extension for `colcon-core <https://github.com/colcon/colcon-core>`_ to act as a template for new extensions.

When using this template, be sure to replace all instances of the word "template" in the repository::

   $ find * -type f | xargs sed -i 's/template-package/colcon-package-name/g'
   $ find * -type f | xargs sed -i 's/template_package/colcon_package_name/g'
   $ mv template_package colcon_package_name
   $ grep -iR template *
