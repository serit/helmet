# serit Helm Charts
serit Helm charts repository.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```sh
helm repo add serit https://serit.github.io/helmet
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
serit` to see the charts.

To install the <chart-name> chart:
```sh
helm install my-<chart-name> serit/<chart-name>
```

To uninstall the chart:
```sh
helm delete my-<chart-name>
```

## License

Copyright &copy; 2022 Company.info

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Notice
Serit has used company.info helm chart as a base, and made configuration changes and additions to be compatible with our own helm charts
