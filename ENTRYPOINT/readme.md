entrypoint is also used to run the container just like cmd but are few differeces.
1.we cant override entrypoint.but we can override cmd.
2.we cant override entrypoint.if you try to do so it will go and append the entrypoint cmd.