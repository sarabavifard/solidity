Solidity
========

.. image:: logo.svg
    :width: 120px
    :alt: Solidity logo
    :align: center

سالیدیتی یک زبان شیء گرا و سطح بالا برای پیاده سازی قراردادهای هوشمند می باشد. قراردادهای هوشمند، برنامه هایی هستند که رفتار اکانت ها در داخل حالت اتریوم کنترل می کنند.

سالیدیتی یک   `زبان آکلادی (یا curly-bracket language) <https://en.wikipedia.org/wiki/List_of_programming_languages_by_type#Curly-bracket_languages>`_ می باشد. 
از زبان C++، پایتون وجاوا اسکریپت تأثیر گرفته و برای هدف قراردادن ماشین مجازی اتریوم (یا Ethereum Virtual Machine (EVM)) طراحی شده است.

سالیدیتی از نوع استاتیک می باشد، از ویژگی های ارث بری، کتابخانه هاو انواع پیچیده تعریف شده توسط کاربر پشتیبانی می کند. 

با سالیدیتی می توانید قراردادهایی برای کاربدهایی از قبیل رأی گیری، سرمایه گذاری جمعی، مزایده و کیف پول با امضای جندگانه استفاده کنید.

هنگام استقرار قرادادها باید از آخرین نسخه منتشر شده سالیدیتی استفاده کنید.
به این دلیل که شکستن تغییرات همچنین ویژگی های جدید و رفع باگ ها به طور منظم معرفی می شوند. . مادر حال حاظر از  شماره نسخه  0.x `برای نشان دادن این تغییرات استفاده می کنیم <https://semver.org/#spec-item-4>`_.

.. warning::

  Solidity recently released the 0.8.x version that introduced a lot of breaking
  changes. Make sure you read :doc:`the full list <080-breaking-changes>`.

Ideas for improving Solidity or this documentation are always welcome,
read our :doc:`contributors guide <contributing>` for more details.

Getting Started
---------------

**1. Understand the Smart Contract Basics**

If you are new to the concept of smart contracts we recommend you to get started by digging
into the "Introduction to Smart Contracts" section, which covers:

* :ref:`A simple example smart contract <simple-smart-contract>` written in Solidity.
* :ref:`Blockchain Basics <blockchain-basics>`.
* :ref:`The Ethereum Virtual Machine <the-ethereum-virtual-machine>`.

**2. Get to Know Solidity**

Once you are accustomed to the basics, we recommend you read the :doc:`"Solidity by Example" <solidity-by-example>`
and “Language Description” sections to understand the core concepts of the language.

**3. Install the Solidity Compiler**

There are various ways to install the Solidity compiler,
simply choose your preferred option and follow the steps outlined on the :ref:`installation page <installing-solidity>`.

.. hint::
  You can try out code examples directly in your browser with the
  `Remix IDE <https://remix.ethereum.org>`_. Remix is a web browser based IDE
  that allows you to write, deploy and administer Solidity smart contracts, without
  the need to install Solidity locally.

.. warning::
    As humans write software, it can have bugs. You should follow established
    software development best-practices when writing your smart contracts. This
    includes code review, testing, audits, and correctness proofs. Smart contract
    users are sometimes more confident with code than their authors, and
    blockchains and smart contracts have their own unique issues to
    watch out for, so before working on production code, make sure you read the
    :ref:`security_considerations` section.

**4. Learn More**

If you want to learn more about building decentralized applications on Ethereum, the
`Ethereum Developer Resources <https://ethereum.org/en/developers/>`_
can help you with further general documentation around Ethereum, and a wide selection of tutorials,
tools and development frameworks.

If you have any questions, you can try searching for answers or asking on the
`Ethereum StackExchange <https://ethereum.stackexchange.com/>`_, or
our `Gitter channel <https://gitter.im/ethereum/solidity/>`_.

.. _translations:

Translations
------------

Community volunteers help translate this documentation into several languages.
They have varying degrees of completeness and up-to-dateness. The English
version stands as a reference.

.. note::

   We recently set up a new GitHub organization and translation workflow to help streamline the
   community efforts. Please refer to the `translation guide <https://github.com/solidity-docs/translation-guide>`_
   for information on how to contribute to the community translations moving forward.

* `فرانسوی  <https://solidity-fr.readthedocs.io>`_ (in progress)
* `ایتالیایی <https://github.com/damianoazzolini/solidity>`_ (in progress)
* `ژاپنی  <https://solidity-jp.readthedocs.io>`_
* `کره ای <https://solidity-kr.readthedocs.io>`_ (in progress)
* `روسی  <https://github.com/ethereum/wiki/wiki/%5BRussian%5D-%D0%A0%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%BF%D0%BE-Solidity>`_ (rather outdated)
* `چینی  <https://learnblockchain.cn/docs/solidity/>`_ (in progress)
* `اسپانیایی <https://solidity-es.readthedocs.io>`_
* `ترکی <https://github.com/denizozzgur/Solidity_TR/blob/master/README.md>`_ (partial)

فهرست
========

:ref:`Keyword Index <genindex>`, :ref:`Search Page <search>`

.. toctree::
   :maxdepth: 2
   :caption: Basics

   introduction-to-smart-contracts.rst
   installing-solidity.rst
   solidity-by-example.rst

.. toctree::
   :maxdepth: 2
   :caption: Language Description

   layout-of-source-files.rst
   structure-of-a-contract.rst
   types.rst
   units-and-global-variables.rst
   control-structures.rst
   contracts.rst
   assembly.rst
   cheatsheet.rst
   grammar.rst

.. toctree::
   :maxdepth: 2
   :caption: Compiler

   using-the-compiler.rst
   analysing-compilation-output.rst

.. toctree::
   :maxdepth: 2
   :caption: Internals

   internals/layout_in_storage.rst
   internals/layout_in_memory.rst
   internals/layout_in_calldata.rst
   internals/variable_cleanup.rst
   internals/source_mappings.rst
   internals/optimizer.rst
   metadata.rst
   abi-spec.rst

.. toctree::
   :maxdepth: 2
   :caption: Additional Material

   050-breaking-changes.rst
   060-breaking-changes.rst
   070-breaking-changes.rst
   080-breaking-changes.rst
   natspec-format.rst
   security-considerations.rst
   smtchecker.rst
   resources.rst
   yul.rst
   style-guide.rst
   common-patterns.rst
   bugs.rst
   contributing.rst
   brand-guide.rst
   language-influences.rst
