Frequent Reasons to fail the project:

| Fail Reason                      | Failcount |
| -------------------------------- | --------- |
| Should work with very long text 1000+ characters  | 1         |
input ./client "" text is error
input ./client "0 || 1" text is error (<=0 process does not exist, 1 is init process)
