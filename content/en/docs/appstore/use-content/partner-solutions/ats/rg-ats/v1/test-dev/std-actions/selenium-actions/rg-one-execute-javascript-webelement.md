---
title: "Execute Javascript WebElement"
url: /appstore/partner-solutions/ats/rg-one-execute-javascript-webelement/
---

## 1 Description

Executes the provided JavaScript snippet.
Runs asynchronous when Timeout is set.
Returns a string.

## 2 Usage

Pass the script you want to execute as parameter for the action. You have to set a WebElement as return value, otherwise the action will fail.
The optional arguments are stored in an array and can be used in your script. For example type "arguments[0]" to get the value of the Argument 0 parameter.

## 3 Input Parameters

Name | Datatype | Required | Description
---- | -------- | ------- | ---------------
Script | String | yes | The JavaScript source code you want to Execute
Timeout(ms) | Integer | no | The time in milliseconds for the script to finish
Argument 0 | any | no | Argument to use in the JavaScript code
Argument 1 | any | no | Argument to use in the JavaScript code
Argument 2 | any | no | Argument to use in the JavaScript code
Argument 3 | any | no | Argument to use in the JavaScript code

## 4 Return Value

Name | Datatype | Description
---- | --------- | ---------------
Script Result | WebElement | The return value set in the script.
