Welcome to SymbiFlow examples!
==============================

This guide explains how to get started with SymbiFlow and build example designs
from the `SymbiFlow Examples <https://github.com/symbiflow/symbiflow-examples>`_
GitHub repository. It currently focuses on the following FPGA families:

- Artix-7 from Xilinx,
- EOS S3 from QuickLogic.

Follow this guide to:

- :doc:`install SymbiFlow <getting-symbiflow>` and all of its dependencies,
- :doc:`build <building-examples>` and :doc:`upload <running-examples>`
  example designs onto the devboard of your choice.
- compile and run :doc:`your own designs<personal-designs>` using the Symbiflow toolchain.
- :doc:`customize the Makefile<customizing-makefiles>` for your own designs.
- gain valuable information about `Understanding Toolchain Commands in Symbiflow <understanding-commands.html>`_


About SymbiFlow
---------------

SymbiFlow is a fully open source toolchain for the development of FPGAs,
currently targeting chips from multiple vendors, e.g.:

- Xilinx 7-Series
- Lattice iCE40
- Lattice ECP5 FPGAs
- QuickLogic EOS S3

.. toctree::
   :maxdepth: 2
   :caption: Sections

   getting-symbiflow
   building-examples
   running-examples
   personal-designs
   customizing-makefiles
   understanding-commands
