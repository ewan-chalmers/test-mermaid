# test

Test whether [mermaid in markdown](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/) works.

If it does, this will render a diagram:

```mermaid
flowchart TD;
A[Deploy to Production] --> B{Is it Friday?};
B -- Yes --> C[Do not deploy!];
B -- No --> D[Run deploy.sh to deploy];
C ----> E[Enjoy your weekend!];
D ----> E[Enjoy your weekend!];
```

- Test in [github.com](https://github.com/ewan-chalmers/test-mermaid)
- Test in [github.ibm.com](https://github.ibm.com/ewan-chalmers/test-mermaid)
