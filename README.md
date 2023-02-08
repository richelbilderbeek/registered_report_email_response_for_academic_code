# registered_report_email_response_for_academic_code

A Registered Report for how email requests for acedemic analysis code is handled

## Hypothesis

 * Email responses are lower for 'Code available upon reasonable request'
   than for those without the qualifier 'reasonable'
 * If code is emailed, it is unlikelier to have no licence, 
   compared to code that is published directly

## Method

 * Scan the PDFs of published manuscripts for 'Code available upon reasonable request'
   and 'Code available upon request'
 * Send the corresponding author of that paper a standard email requesting for code
 * Keep sending every month until there is a reponse
   * If 'no', record this
   * If 'yes':
     * measure if there is a license
     * If there is no license, ask if the code can be published
       * Record answer
