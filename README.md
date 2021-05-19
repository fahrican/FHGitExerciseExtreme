# FHGitExerciseExtreme
This is test git repo for the FH WKW



override suspend fun getKeyWordQuery(userKeywordInput: String): BitcoinResponse {
        return newsApiService.getUserSearchInput(
            userKeywordInput,
            BuildConfig.API_CONFIG,
            ENGLISH,
            RELEVANCY
        )
    }


