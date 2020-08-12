# Comment the lines present between any tags

This code will help you find ways to comment a block of lines along with their tags.

## Usage

Uploaded example comments the lines in Env.conf file, which is present locally.
But code can work in remote server files as well.

In Comment.yml
First task

        path: [ Give complete path of your file here ]
        after: "<resource server1>\n" [Give the open tag here with \n]
        before: "</resource>" [Give the end tag here]
in second task

        regexp: "<resource server1>"  [Give the open tag here]
        replace: "#<resource server1>" [Give the open tag here with #]

## Contributing
Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.
