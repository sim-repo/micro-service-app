git add . && git commit -m "f" && git push
helm package ./redis .
helm repo index .
