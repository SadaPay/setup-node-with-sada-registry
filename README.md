# Composite action to setup node with sadapay registry

This works just like any other action you are currently using. See example below


```
 - name: Run setup-node-with-sada-registry action
        uses: SadaPay/setup-node-with-sada-registry@v1
        with:
          GH_PACKAGES_READ_TOKEN: ${{ secrets.GH_PACKAGES_READ_TOKEN }}
```
