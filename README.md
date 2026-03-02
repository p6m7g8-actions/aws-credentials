# p6m7g8-actions/aws-credentials

- [p6m7g8-actions/aws-credentials](#p6m7g8-actionsaws-credentials)
  - [Usage](#usage)

## Usage

```yml
      - name: Configure AWS Credentials
        uses: p6m7g8-actions/aws-credentials@main
        with:
          aws-access-key-id: ${{ secrets.AWS_ACCESS_KEY_ID }}
          aws-secret-access-key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
          aws-region: us-east-1
```
