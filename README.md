# Open Eastern Orthodox Commentary Version (OEOCV)

This project is intended to create a public domain version of the Bible designed for Eastern Orthodox Christians. This is mainly based on the [World English Bible](ebible.org) (but is not in any way affiliated with it or its creators) with some text from other sources. It is currently a work in progress and is not ready for use.

The OEOCV is not a new translation nor is it intended to have new commentary, although some may appear if someone chooses to contribute it. The purpose of this version is to insert relevant commentary from early Christians. This commentary could either explain the Church's position on a topic or it may provide a heretical interpretation along with a rebuttal in order to demonstrate the history behind a certain interpretation. Non-canonical books, such as the Shephard of Hermas, may be included if it is deemed useful.

This project uses the USFM file format and can be converted into other formats with tools such as the [BibleMultiConverter](https://github.com/schierlm/BibleMultiConverter).

Since this is a public domain work, you are free to redistribute and modify it as you see fit. However, if you modify this version, please name it something other than the Open Eastern Orthodox Commentary Version (OEOCV) in order to avoid confusion.


## Translation

- Based on the [World English Bible](https://ebible.org/find/details.php?id=eng-web).
- When there are differences between the Septuagint and Masoretic Text, the Septuagint version is used from [eBible.org's modification of the Brenton translation](https://ebible.org/eng-lxx2012/).
- Because this is a combination of multiple public domain works, the writing style may be inconsistent.
- Uses traditional pronouns.
- Removed the Strong's Concordance references since this is focused on the Greek version of the Old Testament, not the Hebrew version. This also reduces the file size and makes it easier to edit.
- In the future, we may capitalize pronouns referring to God (this is a low priority and will only be done after getting this version of the Bible to a useful state).
- Due to the author's request to rename modifications of the World English Bible, references to it have been removed (with the exception to acknowledge it and give credit for parts that have been copied).


## Contributing

You may contribute by doing any of the following:

- Submitting links to public domain commentaries on the Bible. Ancient commentaries are preferred (even from non-Christians since these can be used to help understand misconceptions or translation issues) but more modern Eastern Orthodox commentary is welcome too.
- Finding verses that would benefit from commentary and submitting relevent quotes with citations. Feel free to submit verses that need commentary, even if you do not know of any relevant quotes for it.
- Pointing out any issues with grammar, wording, correctness of the commentary, etc.
- Pointing out any potential copyright issues.
- Making a list of verses with pronouns referring to God in order to make it easier to capitalize someday.
- Anything else you think might help.


## TODO

- Create a simple Javascript form to help contributers format footnotes.
- Create shell scripts that help people import this to various editors.
- Edit the `\id` tag in each file (https://ubsicap.github.io/usfm/identification/index.html)