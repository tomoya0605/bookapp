
## users テーブル

| Column   | Type   | Options     |
| -------- | ------ | ----------- |
| name     | string | null: false |
| email    | string | null: false |
| password | string | null: false |

### Association

- has_many :books


## books テーブル

| Column | Type   | Options     |
| ------ | ------ | ----------- |
| name   | string | null: false |
