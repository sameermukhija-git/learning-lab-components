# createIssue

## Options

| Title | Property | Description | Default | Required |
| :---- | :--- | :---------- | :------ | :------- |
| Title | `title` | The title of the issue to be created | `` | ✔ |
| Body | `body` | The body of the issue to be generated - this should be a markdown response file name. | `` | ✔ |
| Comments | `comments` | A list of response files that will be posted to the issue as comments upon creation. | `` |  |
| Data | `data` | An object of data that will be used in the response template. This can include values from the webhook payload, information about the user, or values returned from previous actions in the same step. | `` |  |
