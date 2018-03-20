# TENDER 2.0

This is a platform for tender creation and contract assignment process.Through this we attempt to bring transparency in the process using a emerging Block-Chain Technology.

## Problem Statement
Lack of transparency in the tendering process and assigning contracts to agencies for road development has led to unwise use of money and the spirit of speculation. 

## Proposed Solution
We plan to bring transparency in this system by making the records of tenders public using Blockchain technology. Bidding of tenders will take place on our platform and comparatives of bids will be verified by all.
Once the tenders have been approved, the final payment system for the contract will also be blockchain based payment which ensures that no records have been tempered with and defect liability clauses in contract are implemented properly. 

## Use Cases

There are four main actors interacting with the system.

#### Government Official
- Creates new tenders 
- Monitor existing tenders
- Give the contract for a particular tender to the contractor
- Monitor ongoing contracts
- Verify the task completed by the contractor

#### Contractor
- View all Tenders
- Place bids on the active Tenders
- Gets contract assigned from Government officials
- Withdraw Tokens once task completion verified by Officials

#### Verifier
- Authenticates Government officials and contractors

#### Common People
- View all tenders
- View status of all ongoing contracts
- View the insights of past contracts

## Benefits
* ###### Transparency in System
* ###### Diminishing Corruption
* ###### No one can view bids before closing date
* ###### Decentralized Database
* ###### Login using only wallet address
* ###### Encrypted data
* ###### Milestone (Task Completion) Tracking
* ###### Review time with penalty
* ###### Own Cryptocurrency

## Prerequisites
#### Geth Client
			https://geth.ethereum.org/downloads/
    
#### Node.js
			https://nodejs.org/en/download/
            
#### truffle
			http://truffleframework.com/docs/getting_started/installation
			
#### Ganache (optional)
			http://truffleframework.com/ganache/

#### MetaMask
			https://metamask.io/

## Running the Dapp locally

You can run the app locally using truffle. 

    git clone https://github.com/scoco97/TenderSystem---Blockchain
    cd TenderSystem---Blockchain
    npm install -g truffle     // if not already installed
    npm install truffle-default-builder --save
    truffle serve

You'll need to either be running a local ethereum node, or be using an Ethereum browser like Mist or Metamask. Point your Ethereum browser at the Ropsten TestNet.

Access your locally running app at `http://localhost:8080`

Then you have to map the addresses of the the contracts deployed in the web3_main.js, and your application is ready to run.            
    
## Built With

* [Vue.js](https://vuejs.org/v2/guide/index.html) - The web framework used
* [Ethereum](https://www.ethereum.org/) - Used for smart contract deployment

## Screenshots
##### Creating Tender 
![Creating Tender](https://lh3.googleusercontent.com/yOHTbnwyxaU7DnOYLcQlkMky0WV6J4vyLd826pp8sK0e5dd0v7qwvV4GrCR4vD9HOCUpyJmiKeEMx1HkSx-eNXeJknAwSCKuqgDls78YwdxfLI3YGdjET3dI3Bo5fFuZMelXvDJ-WcGl2I5H2sR5Y1m7k44mIzzmFACySlwqhCigx2RWGonmtMlxePsExwsHceac59PqgPuQ8UxRrKqvHLclTJkT1L-I3AnrKQ-wqGn7IZcP2pOUq1sOS9kQExgemFfGz1PHP3R4yPh-hSdhIO48S40TYLdvL9CRIAV_3E9d4EMQqbYJIEq6_ylrGl4VkFCdwaCspcMjUDGNjMIwLkHLDrnak5Xmuf0I8yg-8lUKNwAQz6e9-hYxqXHWDx4TE_03JCk2Rrb5QhDcoTgbzg6yk6l50hpiCCO8wN7SxTCanFL_QGNgdJ6Io6QEx2q7YjjNIt8wcZBAP6R7sfkI_4z_YFjHBcUyEjIE2XFTIYhdvlVZqBOWzjEdw6xGcRaf8RJsjM_aYGZ4SWNuNIuJ9ZNcRo5jcw7BdLrVlpT1xn5z8Cs_4fGyZ0q8ZoblVMUBg3J0DOyMY9_wag4UaQqjtoNJxj6G8KkQgLpsdA=w1199-h613-no)

##### Existing Tender
![Existing Tender](https://lh3.googleusercontent.com/C0JbJ0M35W4idDJbo5wgmTtkNlJR-egZNMGVYXnTWVpWk9BfKeiG1-g0BGSjUClqd7xdpa4mPW3V9aCeSYenac6K_A8KecrKZoZMmS1h_UBbc60KDDaOGmmgVbztbAFPl_ByPbLZQ33BE9yBQMpAfC4XxPoQXODlzZ3iBkWZf9r8fn9-yEZxgmHsuccuR3Bo2K-PK4Aui412m1LWdZifsVJ_fNmNeOmV2qp1dSafrHnzBz8FUF42du3ctJrrFpCICU7TS4jF4oxdmcM1-1vp5sFyUt0-lXh_J-n3j1OprAkyoXmKcRNcEF8Lyw8iU0zKJOZHm7qNjUcda-YLWqFMo2Z1pMWC0Qd_VhXlbe0K6JsUvz5GGktVJbeEjddUWOzaI6CiHxfY_7I-WvVCX0WBVqErcocJS93Yrb7BnL8R68wakruECEAlBg_QG76CzCKY9BkhVhnxvLGjLaabsBmtQay_96pRTbY7G22Z3eRnt1lWmD5Tdb42cYF1a7HizHY0_1yjM4NFDBajmx83ZOICOmnRwM5TwNq3aq841r8ZmjdZOH3ap-_2iNPF8C2VbwGu63RJpZuCnOFjCt_GWisUu563BfDQ3Z8gUaZETg=w1090-h613-no)

##### Expired Tender
![Expired Tender](https://lh3.googleusercontent.com/-P5eZcJGQAx36Hxcx-MWo3-_XC8kG0uzdRgXqs_im1humxpGxCtGQH6CVrpln17vB4k_dCpOqINvpE9pELOnvXDW2HqZus6sizS1OriCkuALlpJVbyPUzNv0gudtW-SenwvNq9OFnTmPfGITQiviyqeSZejkVVLcndcz8aR3Xo8wwyaaOhyavS-KDw607Xu8vCUNxJt535p_Q0SIiYTtHqrN96dYzKFGsOeuaTqZuXZeX9hYyRi_44I19_Ufr6zfRHC7GsCdrBxo0MgH9Qr5oFeDcgeow5mBfqDBPZVTqzx1yBInShlOBW69XzlxHOt3dC8iQUMud8POWSNxNZjuKqfj76pZwjH3KcC1yluy1iVbSt3GzYz0j4WcpfadEz_kKGLQRZYIdX0OR6jOZiOUY173fAWurbAx1KY1n5QVXV5BKJPNLOBhIa0rec9hC9e1Ks73-HUbA8_GRFEDdeDZCe61dvdfWClFPxpgHDqQzNZopbazh2av0G097pzD4kE6jP_9WgY2dYVvgIPGBDtFP_mq-N-oD7eQZkJ2dQmx5rCkykm77xkA4rcUietag46lZWJ1Ej5cJ-PWFS2cOIaL-qdt3C507zApggGEhw=w1090-h613-no)

##### Ongoing Contracts
![Ongoing Contracts](https://lh3.googleusercontent.com/u1nLfc0WuhqhFqRejUF5fpEmL7aN5AV1DgMfGpwRrNeLw9dlliggXntlIQO64eS6ht_C76QIvNsPf93JtVWQonGUBgnl5ewHpqqPpVuyaSqvQhPTAZrUlt9e9UyM9WLS4Tz1NrooX_Bjz5H5KBKkP33VDd3AIFzNjfQ8emlRrrj6jrDV2UPCaYP41YFdDyL_rjR_CzfWsKXkDXCre3XcHjC1Gx5_GtnW8fsYfGT71tBRsYrZkvPIoKdzLHJZijf6HeRdCj8MA6ZHH_0zTHr2TsO-cwXM6Nd1QqJgAnV-x24J58ntbU86jYW4DvAR9o-rXm3TlwYyWQog2RQgDwNFdYkSND7a-nrcf3s3jJjBC2252yCOGk2OFUEphdd_u6dEYQAAx9LBfJhnVdtRV2TFsrRmQMyf94t6ocfoSjV8FzRS6wt-BvrfTgY2PkHSSjBxoyBUoe1Gb8GHX6JgjkkNJy0ESOuoAqAfzgt7i7Yq0w3g7L38tIHzlkCz2TxSnWEiCF1qMipVbAl8DwmhmySpt671ULcLCLXA8K5x8Ichc7zjwNhl6haBbasXFbh_CAxC34a1vR9szdeWu-Rz7aIS9ttnAD9VfreapaqUlA=w1090-h613-no)

##### Placed Bids
![Placed Bids](https://lh3.googleusercontent.com/U-ZcTyz36TKfo6LqidB_4puSakuA2_bDdpqsE1t-dJr02eFpfR5Szw8dKofgQW9FvO7BT_bHSBowwh9MOLe5zKk_ilKPKaLzGNvJd006fyusFwlrmNmdNl9_42EMnFhF7sA6RZwSy10YWL8KPwL6rUORgDWL5AN9WvsfDTbyZn0Wq0nW_8K6XZtJIyvE5HYx33_gUmyh34LaDF8jSzASD0T-_oBBsFsDbXr9Ku-Hx_FkFHTEif1-b6hW0qWW2i9oeSS-5y_pUFb6C3t897tDXwLFLd6C5uYpdeqMQZRLFWs4vxe3fFwCdFSZ4Q5ME3LLbwtNKQTZ6mFMeiKmSetKd1QLfq15G-SIhh7Zui9Ae9QQGieX0wZgIuWrukJgQQgE1q4HElhQ19_BOKTOCnlw8IbmZfr3MWkKmHk57a4lbHFQSUN-9ukXA54f0cS2zA8_cOheKN4rctUoEm0M_dcOtWGuAHZdE5SRKJEDwzPlp9sA6hJvxj_l1Pfwnkkg6lznER_YY82K7a2m0vT-8wy7qluzNpQXsjIPVBzpTaogKV6QuXAsji0m85v1yTnrahScpXYzTWn5vcETeS0pnJti640qvqOi7DhbId_sTA=w1090-h613-no)

##### Placing Bids
![Placing Bids](https://lh3.googleusercontent.com/9v_jtj5tu3SrUiO0PgC8EN6B9R-c7jOT-6G7zitl3OPB4jzo5tC_KAdGqIKwhdBEza6-JUcmx4cMNAi09koa7IPQp5mw9hv_ip9ItNIr7FtrxLOpe17-8FUh8GPEygnOO2uhO8zp81Anli9gC1yynh-FwJCX04TIIv0ww_P35x4y_hAIqeu0qaN9ZaUh-E4iYDOI-0R3WkSj2J3nb3vmkAU0hdcdP9aHnDPA55ctdaVSn8pycy4ylaJeWoGHYCU71uYpn6ZmqQEyVN8DD8Lnc16_Pdd4_14SvsIIIShOmGJWo9ENLeZ1-XLw4BywtDr3lfsdm_ZPl2CTxPcK-0B3v0UKqhfT0mCSpEPfymNaJANPH2J0x8TktwGSHmWE-a18qtvViFXyDhYNygBWCVxGpw2uHHcW25ENzrhcxirgL4RwmKJaOGqO-vof-BRMdkO7wPAhzGIBvwt3R54ISJS9tbM2TlcixXpecjOAiGGb6_HzZ9Hmat8vWcP4ZfbtVhGWabIgkRSYxrAwhdFsASw-XI1LJrybhM7lymQXG1BVa3qv21M8OqM3CkDfT9Kzs18P14kxS63wMJOV17blJ2OWewqh6ycQBgXHpg18qA=w1176-h613-no)

##### Tender To Contract
![Tender To Contract](https://lh3.googleusercontent.com/tl89SbMjAmCgQ8eGROKa_gY5a60Vdp8UdmZDHaeME9ciRh5mjXAi0BD-pPRyAZu2R-MDrHSBjItWdXxfGe0VdwyrRBqlOnHcuAgwg8nnl1PbWdad8bA-hoVjghpSDSP3wzHAQ5rV8_u2E4NgXs0XHsh60kdTbIQxqzww7PrBKsfyxV3i9GfwJXvPH2qduz2Vj0GWpVUYq9d0vjmvH7dfobavi4BH8cPX20DEUTRfNmpW2alLU7nwmZ_27y5srFJ5qbBGtwQnjMT6t7ZY3JkIjF12U3jGQNfhKsQF8y-j4KogiwsL6E2IAx8CS0mwJPzQLdcD8XKAklChyfd-M_2xV0AH8m0j9MFrl-QocpeGGP9V7vKKVbsVKNp6lDFp9GJCwvG7lDhJRloRO32hArPomyzdn_FKloUYc8_20XP3wELuaw7XCbyPS2ulIS9hRSZVAKrTzqRPAOvxw4YL9grzYLHgVneT_SFlJK9z_ihDMZjQfgn2YAi40iME5njF_8SCAo7mVfJb8xVSO2g46nff8dhIvbBu9ie0bb1ZEnMEQyPUZiwijMODfqzKAAL0SKMWOgcRHfPvVS4gZ-8u00k5cO6_KwcFs8J4w93xqA=w1090-h613-no)

##### Tender To Contract
![Tender To Contractr](https://lh3.googleusercontent.com/h8G3yd3jDFkGprnWXHbTUyukc8wZw3uW8rM0ZuwZPfRi0eSE86iag-qoQ6EkujvWFKNByoE5-wi7FBPAexhsEZaKKHrc72SRw-xDvRWqljYNOHaJstSI1yU4SyxdIP_0xIU-lk3TAtVRwHrn_RUpPm5aytDG2Vg5RsUA8E4cqRqy_4Hagv2fnUjiZeC127cwHdIvcc3hi6SuDItytFPLvSCaXPcksgdO3RQI0Am5stYFKzh1ssbOc4D-CE2SZGm3X_Djdg8vfaLDLHJXCJKdvIvznMajWCxv8o223LL70RtqVgsWGC4fxmlK5GWrDXM23-6Nk7oo3fjEv1v-LlVKWeWEJptyy8PGx26rd6_AQBgrD7quyFSuljv1VX92RuLOJNT1Qf9P6fujDdMSk_q8buAFE6qBuM54Ss1O_JATZHjVTeRyJIEcJMcao4YqK0CyoQaOHLD6gmFOY7FHTwvJf09YXhjRj7uAlfl1soZXQkdVRuiKoIc5m10nXkKFqQZ9px3uKR48stu1V0HMBTq-blUvlyJ-n_4QbWnzqUQauopihGlHGXLle_P_M4enP1wiA0WY3EbEnEb164_KEwxh52Uk_Zmt3UThz1FC0Q=w1090-h613-no)

##### Verify Docs
![Verify Docs](https://lh3.googleusercontent.com/66OYhJtucNtTrEPA55w-wXLHjez_dln4Du8kyYAT6Y-qwbxnHzouhtVDznsWXDp4BMz-E4Ev6l86B7HRyF-rmuqMc8dythUvP8rN2hZjOjMEGD7TXz2I3JA1P5Jbx3hMwLl51XO8EGcZBRnzaO-tgcikAJi3v-m4YDWodoqu_zECIGBjxZITCqfjNheumV9lnkBDAWQDq81VJfgtFbsnxUPdMCDj4fgYAievr6GkX-7cx0bQQdzQaRHfGMH5_0CRlWWYCegH_qIMcOuURpDIGvg6xp4r9Up-MGAanY3QSElEM5m4Wg9lAqbLKQvV4Pcs4P12_zZn5-bspl3E3az1zF1jQCNk0KjhfKIHPDjVyF_RIiQM35_-AWBowY6osAfJjkwD3SmYR2Lbahqg39Xs0AIOkHwrJXvXtL4f9rVZNeEpHZxXJItv11W_AY3pw1ThgevyHB8pAvvKfOVG0XtXxU0N5ioqfn-vt6Au27ZGiZi9gKkQ_dV7o9t-oHaO__poXV5GBqBir_LGfrh6v0pLHVN0gthLWMPmZwdpek12FbmlaSt1CKRERUIhdWKzStfiku1rXweXDU5JuAIMHUuf171dEuzki-8E2rXTdg=w1090-h613-no)

##### Verify Officer
![Verify Officer](https://lh3.googleusercontent.com/ATu5i9uvxZh9fpNJWuntoWQqud_teE5i3Et_w863gSmBdTe-HRK6_LPij3I-1hAJmKeQ0s6OqQsdQLGeOr_hwexvBjcX1pVZ0iOMcHusuxQt67U8-loYA-466oa3VOWl58Dm4B1t7StRktRUL62gDJd0ywSg7QzdvK9_KqW2VWv_AGr35Dme936jdmnvrSWJUTj4bZfOGaPT1jTCtf5jiXrCT9xBbCJzhdSo2pu8ksi589CVbFSBv7mfw4-igPBpenzCRfaksHCseNHoREVk-UcLE0AddNmp7A0gPY4vGg-bT9xhyIBNq4ZXYZrlzFOrjwutrQ4xWcLy8uuR3GEw1FclfMlreC_UZLWjxM-XVSi8lP7aPC6ilFJRPrIO3gt1-WXCtdUQxwz41yt-WDQQmteq7mWu8ixJ9cmBIbWA9y1gl1ozto1Fy7MZzqqJHtw0RHHy6cTxo3p0wbR_izQ6g6zr933In33C7IqSQou9r2zt_XJ8z5UDJK9Fl10ScFozgfsKnK-TfE0vEHG2oSHQB-3I-L7lTQbl2adSAdo69IxFtFfj_DEJCRAWb0N00FoqlhrjzGapGs6kxEjxTU7mXyeV3fzRVb90_A-jtw=w1090-h613-no)

##### View Documents To Verify
![View DOcs TO Verify](https://lh3.googleusercontent.com/WKPqoSCkOiSAFmO2Jivm-my5Ez_QDrnY-1sMuLzVL9KjDQLBmd_zTnUE2wkS2O2xu1a232UNRHsstWtPqEY6ws9Fn7BSLNP9S3GceaIFpO7lyivBG4NPy-Y9CK1qve_3K-Y9bEQBb4CA5VoALJ7WYsThswOPewfV_cLtTJ2hzSQYGEAhud4WN0pgbR3hxG14RKBbkMlpjlRtdQVxjgBCTLDXGihdTtRoZzfUSyYWDldkNfOivu3dJs0KTqWANAHrSKOAZKPGyDNKy8ki76EQApyqOoNriarsDIRTf20m3nHYjlmZqKAOTd1d-K6VZmiGKZauR39nStfFZsIH_CkLUljH6noRVf4uUv0zeSEYqG25D_KQh8ZEHXyi_o0u9y1kF5W6MJe4gbjqh6SB7xRd3--JtSo4xkGJ-KOe_C4zROAeGvZ8bP5vhI9PU8A49i4C9N2leySf8Hp9kHVoCLMXoqX5j1UmNhQdXz31T5MTCWELvic47K8p68JQBZLrx5aPNF9KnRP49CTVPBkn9uh_YJ9IVqH1nLpbDAIkNZJR7m74PKhDUDNeqkwIuZVjZNu5zMePERSGsQ341X-94XuoOYKpMPX1VDvIZycHZA=w1090-h613-no)

## Presentation
* [Tender 2.0](http://prezi.com/zp0s9b-1qmq2/?utm_campaign=share&utm_medium=copy)
## Authors

* **Siddhesh Rane** - *Initial work*
* **Siddhesh Gangan** - *Initial work* 
* **Yash Jain** - *Initial work*
* **Pranamya Jain** - *Initial work*




