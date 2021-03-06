# actions
Github Actions to help developers with common CI/CD tasks

## Deploy
- [Expo Publish](./src/expo/publish.yml)
  - Automate your deploys to Expo Cloud
- [Expo Preview Channel](./src/expo/preview.yml)
  - Create Preview Releases on PRs with QR Code comment on success, better DevEx in code review
- [Heroku](https://github.com/marketplace/actions/deploy-to-heroku)

## Lint
- [Rubocop](./src/rails/rubocop.yml)
- [ESLint + Reviewdog](./src/eslint/reviewdog.yml)
- [Commitlint](./src/commitlint/conventional.yml)
  - [Gitmoji](./src/commitlint/gitmoji.yml)

## Test
- [Rails rspec](./src/rails/rspec/mongo_redis.yml)

### Feedback
- [Test Reporter](https://github.com/marketplace/actions/test-reporter)
  - Seems like a nice way to visualize test data on pipeline
- [Jest Coverage Report](./src/jest/pr-coverage-report.yml)
  - Show test results on PR comment
- [DangerJS](https://danger.systems/js/)
  - Automatic feedback, code review triage

## 🚧 Repo Management

### labelling
- [DOC on labelling issues](https://docs.github.com/en/actions/managing-issues-and-pull-requests/adding-labels-to-issues)
- [regex-issue-labeler](https://github.com/marketplace/actions/regex-issue-labeler)
  - add labels based on regex match
- [label actions](https://github.com/marketplace/actions/label-actions)
  - uses yaml like format to match, can also control some actions
- Honorable mention: [issues-helper](https://github.com/marketplace/actions/issues-helper)
  - [en-US](https://github.com/actions-cool/issues-helper/blob/main/README.en-US.md)

## Releases
- [Semantic Release + Github Action](https://github.com/semantic-release/semantic-release/blob/master/docs/recipes/ci-configurations/github-actions.md)
  - [repo](https://github.com/semantic-release/semantic-release)
  - [gitmoji plugin](https://github.com/momocow/semantic-release-gitmoji)
- [GH Release](https://github.com/marketplace/actions/gh-release)
  - Creates Releases
- [Release Drafter](https://github.com/marketplace/actions/release-drafter)
  - PR based release drafting
- [Changelog generate](https://github.com/marketplace/actions/generate-changelog)
- [Auto](https://intuit.github.io/auto/docs)
