# Releasing a new version

## Requirements
There are two GitHub workflows handling the publication process.
The workflows need API keys for Modrinth and Curseforge set in the repository secrets settings:  
Settings > Secrets and Variables > Actions > Repository Secrets  
`CURSEFORGE_TOKEN`  
`MODRINTH_TOKEN`

## Release procedure
1. Go to Actions tab and select `Create Draft Release with Artifacts` in the left.
2. In the right, pick run workflow and insert the version number to release e.g., 1.2.3
- The workflow will create both, the mod JAR and the resourcepack zip
- The workflow will create a DRAFT github release and git tag
- The created artifacts will be automatically attached to the release DRAFT

6. Go to github releases and edit the release draft - add the changelog to the description
7. Test the generated artifacts (you surly do that right? right?)
8. Publish the github release
- The second workflow will be automatically triggered by the release publish
- The workflow will publish both artifacts to modrinth and curseforge

## Notes
GitHub Pre-Release does not trigger the workflow when published from a draft and will not be published to Modrinth and Curseforge.
