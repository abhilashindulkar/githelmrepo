# githelmrepo

## Instructions
1. Enable Site by configuring GitHub Repo->Security->Pages->Branch->main & Save the settings.
2. Add git chart repo to list of repositories.

   `helm repo add gitrepo https://abhilashindulkar.github.io/githelmrepo`

3. Install helm chart.

   `helm install demo-chart gitrepo/git-helm-chart`

4. CleanUp.
   
   `helm uninstall demo-chart`

   `helm repo remove gitrepo`
