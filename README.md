## Apple Card spending history as OFX file
"Can I import my Apple Card transactions into my financial management program?".

Yes, you can.

ac2ofx makes it possible to import your Apple Card transactions into your financial management program such as Quicken, Moneydance, Microsoft Money ...

It is a simple two-steps process

* Use ac2ofx to convert the "Monthly PDF Statement" into an OFX file.
* Then import the OFX file into your financial management program.

You can download and eval the tool to see if it fits your need.

In eval mode, ac2ofx is fully functional but limits the number of transactions in the OFX file (5 transations). 

You can obtain a key to remove this limit. The cost is $12.99. Send email to ac2ofx@gmail.com

## Prerequisite
You will need Java installed on your machine.
* AdoptOpenJDK.net: [https://adoptopenjdk.net/](https://adoptopenjdk.net/) 

## Download ac2ofx
* [https://bitbucket.org/hleofxquotesteam/dist-applecardstmt/downloads/](https://bitbucket.org/hleofxquotesteam/dist-applecardstmt/downloads/)

## Install ac2ofx
* Unzip ac2ofx-1.0.0.RELEASE.zip
* Go to folder ac2ofx-1.0.0.RELEASE
* Double-click on ac2ofx-1.0.0.RELEASE-exec.jar OR
````
java -jar ac2ofx-1.0.0.RELEASE-exec.jar
````

## Obtain a key
* Send email to ac2ofx@gmail.com.
* To install the key, simply drag-and-drop file license.txt file onto the ac2ofx window. 

## To download Apple Card PDF statements
* Open the Wallet app on iPhone
* Tap your Apple Card
* Tap the “Total Balance” square
* Choose the month of the statement you want
* Select “Download PDF Statement”

## To generate an OFX file
* Drag-and-drop your PDF statement file onto the ac2ofx window.
* ![Tool Window Image](/image01.png)
* A new OFX file will be generated and saved in the same folder as the PDF file.
* For example, if the PDF file is named December-2019.pdf, then the OFX file will be name December-2019.ofx

## To import OFX file
Follow your financial management program instruction to import OFX.

## Help

* Send email to ac2ofx@gmail.com.
* Or log an issue at [https://bitbucket.org/hleofxquotesteam/dist-applecardstmt/issues](https://bitbucket.org/hleofxquotesteam/dist-applecardstmt/issues)

