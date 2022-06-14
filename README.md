all branch

    - master (main branch where we are going to marge all our branch)
        - feature
    - production (real server production workload)
        - hotfix (branches that are quick fixes on production)
    - staging (blue, green, red - duplicate of the production environment and if it all pass tests we'll swap it with production)
    - qa (prefore tests before merging into staging)