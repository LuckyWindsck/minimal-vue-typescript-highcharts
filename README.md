## Warning
This repository is no longer active since a solution is found for the issue.

# minimal-vue-typescript-highcharts
For issue report ([Solution found](https://github.com/highcharts/highcharts/issues/19205#issuecomment-1666856761))

Issue: [Cannot find module 'highcharts' or its corresponding type declarations. ts(2307)](https://github.com/highcharts/highcharts/issues/19205)

# Environment

## Visual Studio Code
```sh
$ code --version
1.79.1
4cb974a7aed77a74c7813bdccd99ee0d04901215
x64
$ code --list-extensions --show-versions | grep Vue
Vue.volar@1.8.1
Vue.vscode-typescript-vue-plugin@1.8.2
```

## Dependencies
```json
{
  "dependencies": {
    "axios": "^1.4.0",
    "highcharts": "11.1.0",
    "vue": "3.3.4"
  },
  "devDependencies": {
    "@vue/tsconfig": "0.4.0",
    "typescript": "5.0.4"
  }
}
```
