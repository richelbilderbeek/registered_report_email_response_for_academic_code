# registered_report_email_response_for_academic_code

A Registered Report for how email requests for acedemic analysis code is handled

## Hypothesis

 * Email responses are lower for 'Code available upon reasonable request'
   than for those without the qualifier 'reasonable'
 * Email responses are lower for earlier studies
   and identical to [Teunis et al., 2015]
 * If code is emailed, it is unlikelier to have no licence, 
   compared to code that is published directly
 * If code is emailed, if it has a license that allows publication of the code,
   authors always either do not respond or respond positively to publication

## Method

 * Scan the PDFs of published manuscripts for 'Code available upon reasonable request' `[R-1]`
   and 'Code available upon request' `[R0]`
 * Send the corresponding author of that paper a standard email requesting for code
 * Keep sending every month until there is a reponse. 
   Measure how often there is no response `[R1]`. If there is a reponse:
   * If 'no', record this `[R2]`
   * If 'yes', record this `[R3]` and
     * measure if there is a license `[R4]`
     * If there is no license, ask if the code can be published using a standard script
       * Record answer yes `[R5]` and no `[R6]`
     * If there is a license, send an email where the code is published
       * Record 'no response' `[R7]`, 'positive response' `[R8]` and 'negative response' `[R9]`

To interpret the emails, `Term_ChatGPT` is used.
In a pilot run, the interpretations from ChatGPT 
is compared to those of humans.

## Results

 * `R-1`: number of published manuscripts with 'Code available upon reasonable request' 
 * `R0`: number of published manuscripts with 'Code available upon request' 
 * `R1`: number of emails unanswered after 6 attempts
 * `R2`: number of emails answered with a 'no'
 * `R3`: number of emails answered with a 'yes'
 * `R4`: number of code with a license
 * `R5`: number of respondents that allows publishing
 * `R6`: number of respondents that disallows publishing

 * Correspondance human interpretation and ChapGPT's interpretation

## Links

 * [Term_ChatGPT](https://github.com/waxdred/Term_ChatGPT): 
   to use Chat-GPT from a terminal


## References

 * [Teunis et al., 2015] Teunis, Teun, Sjoerd PFT Nota, and Joseph H. Schwab. "Do corresponding authors take responsibility for their work? A covert survey." Clinical Orthopaedics and Related Research® 473 (2015): 729-735.
