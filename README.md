<h1 align="center">Welcome to dirwatcher 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/dirwatcher" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/dirwatcher.svg">
  </a>
  <a href="https://mit-license.org/" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/nicodalfonso" target="_blank">
    <img alt="Twitter: nicodalfonso" src="https://img.shields.io/twitter/follow/nicodalfonso.svg?style=social" />
  </a>
</p>

> A long running program that will monitor a specified directory for changes to any files of a type specified by the end user. Determines if any instances of a user-specified string (aka &#34;magic text&#34;) appear in the files being watched, and logs their location.
>
> Inspired by the story of [The Cuckoo's Egg](https://en.wikipedia.org/wiki/The_Cuckoo%27s_Egg).

## Prerequisites

- You have Python 3.9.0 or greater installed locally.

## Usage

```sh
python dirwatcher.py [dir] .[ext] [magic_text]
```

## Example Usage

```sh
python dirwatcher.py ./test .txt hello
```

## Example Output

```sh
2021-03-22 11:48:59,495 __main__	INFO
[MainThread  ]
-------------------------------------------------------------------
Beginning dirwatcher.py
searching for hello in /Users/nicodalfonso/dirwatcher/test
-------------------------------------------------------------------
2021-03-22 11:48:59,495 __main__	INFO
[MainThread  ] Adding test.txt to watchlist
2021-03-22 11:48:59,496 __main__	INFO
[MainThread  ] hello found on line 1 of test.txt
2021-03-22 11:48:59,496 __main__	INFO
[MainThread  ] hello found on line 2 of test.txt
2021-03-22 11:48:59,496 __main__	INFO
[MainThread  ] hello found on line 3 of test.txt
2021-03-22 11:48:59,496 __main__	INFO
[MainThread  ] hello found on line 5 of test.txt
^C2021-03-22 11:50:02,501 __main__	WARNING
[MainThread  ] Received SIGINT
2021-03-22 11:50:02,502 __main__	INFO
[MainThread  ] Exiting
2021-03-22 11:50:02,730 __main__	INFO
[MainThread  ]
-------------------------------------------------------------------
Stopped dirwatcher.py
Uptime was 00:01:3.2699471159999973
-------------------------------------------------------------------
```

## Need Help?

```sh
python dirwatcher.py -h

OR

python dirwatcher.py --help
```

## Author

👤 **Nico D Alfonso**

- Website: https://nicodalfonso.com
- Twitter: [@nicodalfonso](https://twitter.com/nicodalfonso)
- Github: [@nicodalfonso](https://github.com/nicodalfonso)
- LinkedIn: [@nicodalfonso](https://linkedin.com/in/nicodalfonso)

## Acknowledgements

_This project was initially created as a part of the Software Engineering Certification program from [Kenzie Academy](https://kenzie.academy)_

_To see the original instructions and acceptance criteria for this project, please reference [README.old.md](./README.old.md)_

## 📝 License

Copyright © 2021 [Nico D Alfonso](https://github.com/nicodalfonso).<br />
This project is [MIT](https://mit-license.org/) licensed.

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
