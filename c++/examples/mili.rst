MiLi
====

MiLi is a collection of useful C++ libraries, composed only by headers. For more information about this library, visit their `official website <https://code.google.com/p/mili/>`_ or `wiki <https://code.google.com/p/mili/w/list>`_.

You can find here the `MiLi biicode library site <https://www.biicode.com/danielgutson/mili>`_.

The following example shows a simple use for doing type-safe bitwise operations. You can find this and other examples in `the biicode MiLi samples block <https://www.biicode.com/danielgutson/milisamples>`_.

**main_mili.cpp**

.. literalinclude:: /_static/code/cpp/examples/mili/main_mili.cpp
   :language: cpp
   :linenos:

Create a new project and open the example block:

.. code-block:: bash
	
	$ bii init mili_example
	$ cd mili_example
	$ bii open examples/mili

Now build your project and run the executable:

.. code-block:: bash
	
	$ bii build
	$ cd bin
	$ # run executable


You will see next console output:
	
.. code-block:: bash

	kOne   turned on
	kTwo   turned on
	kFour  turned on

	kOne   turned on

	kOne   turned on
	kThree turned on

	<< Operator test: 0x4
	Normal Enum: 0x18
	Normal Enum: 0x20

Any doubts? Do not hesitate to `contact us <http://web.biicode.com/contact-us/>`_ visit our `forum <http://forum.biicode.com/>`_ and feel free to ask any questions.
