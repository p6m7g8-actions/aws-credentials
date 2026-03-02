# p6m7g8-actions/aws-credentials

- [p6m7g8-actions/aws-credentials](#p6m7g8-actionsaws-credentials)
  - [Usage](#usage)

## Usage

```yml
      - name: Configure AWS Credentials
        uses: p6m7g8-actions/aws-credentials@main
        with:
          role-to-assume: arn:aws:iam::123456789012:role/github-actions
          aws-region: us-east-1
```
