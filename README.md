# codosseum-challenges

This repository contains the collective effort of the codosseum team and contributors to create an open database of coding challenges.

The challenges are written in a [well-defined format](./challenge-schema.json) and are therefore easy to read for machines. The challenges in this repository are primarily meant for running [codosseum](https://github.com/codosseum-org/backend) instances, but can, in theory, be incorporated just about anywhere. If you want, you can also just use these as problems to practice your programming skills, without any additional software.

## Contribute Challenges

Do you want to contribute a challenge?

1. Fork this repository
2. Clone your version of the repository to your computer
3. (Optional, but recommended): [set up pre-commit](#pre-commit) (see below) to ensure that your changes can be accepted.
4. Create a new directory for your challenge under the `challenges/` directory of the repository, e.g. `my-challenge` (the name of the directory will be the unique ID of the challenge)
5. Copy the [challenge template](./challenge-template.yml) file to your challenge directory under the name of your challenge, e.g. `cp challenge-template.yml challenges/my-challenge/challenge.yml`. The name of the file must be `challenge.yml`.
6. Edit your challenge file, enter all the relevant information, create a solution in a language of your choice in the same directory
7. Commit and push your changes
8. [Open](https://github.com/codosseum-org/challenges/compare) a pull request

In the future, we will provide a more convenient web UI for submitting challenges.

### Pre-Commit
WIP

## License
The license and copyright information is specified for each challenge individually through the `license` and `author` fields. All challenges in this repository use [free/open licensing](https://en.wikipedia.org/wiki/Free_license). Specifically all challenges are licensed under at least one of the following:

- [Creative Commons Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/4.0/)
- [Creative Commons Attribution](https://creativecommons.org/licenses/by/4.0/)
- [Creative Commons Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)
