# regex-common

## The Ultimate Regex Library for JavaScript! 🎉

Ever found yourself struggling with complicated regex patterns? **regex-common** is here to rescue you from that mess! 🚀

### Features ✨

- Easy to Use: Simple function calls.
- Comprehensive: Covers a wide range of use-cases.
- Efficient: Fast execution times.
- Community-Driven: Open source and ever evolving.

### Installation 📦

```
npm install regex-common
```

### Usage 💡

Here's how to validate a whole number.

```javascript
const { wholeNumbers } = require('regex-common');

if (wholeNumbers.test("42")) {
    console.log("It's a whole number!");
}
```

Want to check for a strong password? No worries!

```javascript
const { strongPassword } = require('regex-common');

if (strongPassword.test("Str0ng@P@ssw0rd")) {
    console.log("That's a strong password!");
}
```
### What we Have? 📖
You can use all the regex below
- wholeNumbers
- decimalNumbers
- wholeAndDecimal
- alphaNumericWithoutSpace
- alphaNumericWithSpace
- strongPassword
- moderateStrongPasswor
- username
- UrlWithHttps
- dateddMMYYYY
- dateYYYYMMdd
- dateddmmmYYYY
- timeHHMM12Hour
- timeHHMM12HourMeridiens
- timeHHMM24Hours
- timeHHMMSS24hours
- htmlTags
- slug
- searchDuplicates
- internationalPhoneNumbers
- filePathFileAndExtension
- socialSecurity
- passport
- emailCommon 
- emailUncommon:
- ipv4
- ipv6
- ipv4or6

### Contribute 🤝

Found a bug or have a suggestion? Open an issue or pull request on [GitHub](https://github.com/robson-melo-dev/regex).

---

## Support the Project 💖

**Love regex-common? Support us with a donation!** 🙏

*Why donate?* 🤔
- **Save Time**: We maintain it, so you don't have to.
- **Mental Peace**: Sleep better, knowing that you're using well-tested code.

[Click here to donate](https://www.paypal.com/donate/?hosted_button_id=C2T5CHZYKXEE4)

*Using regex-common makes you awesome! Spread the word! 🌟*


