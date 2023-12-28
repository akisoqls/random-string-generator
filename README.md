# Random String Generator

Returns a random string.

## examples

```JavaScript
generateRandomString(10); // "hm57vp5J4r"
generateRandomString(8, ["a","p","P","l","e"]); // "PalalPae"
generateRandomString(16, "orange-peel") // "-ag-laagn-n-lra-"
generateRandomString(); // "AgZPEhZVUZRKDSKRctlgx5iibRPdWN8jCOjLxpr8ZnVT9Y9fWl9syJP8gSXjUlr8"
```

## params

- **`length` (optional)**: The length of random string. Default: `64`
- **`charset` (optional)**:  Characters used in random string. Default: `abcdefghijklmnoqprstuvwxyzABCDEFGHIJKLMNOQPRSTUVWXYZ0123456789`

## returns

Returns a string that includes randomly selected characters from the charset.
