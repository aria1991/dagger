---
sidebar_label: gcp
---

# dagger.io/gcp

## #Config

Base Google Cloud Config

### #Config Inputs

| Name             | Type                | Description        |
| -------------    |:-------------:      |:-------------:     |
|*region*          | `string`            |GCP region          |
|*project*         | `string`            |GCP project         |
|*serviceKey*      | `dagger.#Secret`    |GCP service key     |

### #Config Outputs

_No output._

## #GCloud

Re-usable gcloud component

### #GCloud Inputs

| Name                  | Type                | Description        |
| -------------         |:-------------:      |:-------------:     |
|*config.region*        | `string`            |GCP region          |
|*config.project*       | `string`            |GCP project         |
|*config.serviceKey*    | `dagger.#Secret`    |GCP service key     |

### #GCloud Outputs

_No output._