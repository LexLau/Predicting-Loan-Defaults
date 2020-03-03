# Predicting-Loan-Defaults

> Author: Alex Lau

## Table of Contents
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Conclusion](#Conclusion)
- [Data Dictionary](#Data-Dictionary)

## Problem Statement

Many Americans will need to borrow money at some point in their lives, whether to pay for school, a car or a home. If borrowers default on their loans, it is unfortunate for both the borrower as their credit score will be ruined, and for the lender, as their loan may not be recovered. It is important for lenders to decrease this risk as much as possible. Can we predict whether a borrower will default using loan and borrower statistics? We will utilize a series of classification models to find out. We will be measuring based on sensitivity, the percentage of correctly predicted defaulted loans out of the loans that defaulted. We believe it is worse to predict false negative than a false positive.  

## Executive Summary

Sample text here

## Conclusion

sample text

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**id**|object|Lending Club Loan Stats|sample text|
|**member_id**|float|Lending Club Loan Stats|sample text|
|**loan_amnt**|float|Lending Club Loan Stats|sample text|
|**funded_amnt**|float|Lending Club Loan Stats|sample text|
|**funded_amnt_inv**|float|Lending Club Loan Stats|sample text|
|**term**|object|Lending Club Loan Stats|sample text|
|**int_rate**|object|Lending Club Loan Stats|sample text|
|**installment**|float|Lending Club Loan Stats|sample text|
|**grade**|object|Lending Club Loan Stats|sample text|
|**sub_grade**|object|Lending Club Loan Stats|sample text|
|**emp_title**|object|Lending Club Loan Stats|sample text|
|**emp_length**|object|Lending Club Loan Stats|sample text|
|**home_ownership**|object|Lending Club Loan Stats|sample text|
|**annual_inc**|float|Lending Club Loan Stats|sample text|
|**verification_status**|object|Lending Club Loan Stats|sample text|
|**issue_d**|object|Lending Club Loan Stats|sample text|
|**loan_status**|object|Lending Club Loan Stats|sample text|
|**pymnt_plan**|object|Lending Club Loan Stats|sample text|
|**url**|object|Lending Club Loan Stats|sample text|
|**desc**|object|Lending Club Loan Stats|sample text|
|**purpose**|object|Lending Club Loan Stats|sample text|
|**title**|object|Lending Club Loan Stats|sample text|
|**zip_code**|object|Lending Club Loan Stats|sample text|
|**addr_state**|object|Lending Club Loan Stats|sample text|
|**dti**|float|Lending Club Loan Stats|sample text|
|**delinq_2yrs**|float|Lending Club Loan Stats|sample text|
|**earliest_cr_line**|object|Lending Club Loan Stats|sample text|
|**fico_range_low**|float|Lending Club Loan Stats|sample text|
|**fico_range_high**|float|Lending Club Loan Stats|sample text|
|**inq_last_6mths**|float|Lending Club Loan Stats|sample text|
|**mths_since_last_delinq**|float|Lending Club Loan Stats|sample text|
|**mths_since_last_record**|float|Lending Club Loan Stats|sample text|
|**open_acc**|float|Lending Club Loan Stats|sample text|
|**pub_rec**|float|Lending Club Loan Stats|sample text|
|**revol_bal**|float|Lending Club Loan Stats|sample text|
|**revol_util**|object|Lending Club Loan Stats|sample text|
|**total_acc**|float|Lending Club Loan Stats|sample text|
|**initial_list_status**|object|Lending Club Loan Stats|sample text|
|**out_prncp**|float|Lending Club Loan Stats|sample text|
|**out_prncp_inv**|float|Lending Club Loan Stats|sample text|
|**total_pymnt**|float|Lending Club Loan Stats|sample text|
|**total_pymnt_inv**|float|Lending Club Loan Stats|sample text|
|**total_rec_prncp**|float|Lending Club Loan Stats|sample text|
|**total_rec_int**|float|Lending Club Loan Stats|sample text|
|**total_rec_late_fee**|float|Lending Club Loan Stats|sample text|
|**recoveries**|float|Lending Club Loan Stats|sample text|
|**collection_recovery_fee**|float|Lending Club Loan Stats|sample text|
|**last_pymnt_d**|object|Lending Club Loan Stats|sample text|
|**last_pymnt_amnt**|float|Lending Club Loan Stats|sample text|
|**next_pymnt_d**|object|Lending Club Loan Stats|sample text|
|**last_credit_pull_d**|object|Lending Club Loan Stats|sample text|
|**last_fico_range_high**|float|Lending Club Loan Stats|sample text|
|**last_fico_range_low**|float|Lending Club Loan Stats|sample text|
|**collections_12_mths_ex_med**|float|Lending Club Loan Stats|sample text|
|**mths_since_last_major_derog**|float|Lending Club Loan Stats|sample text|
|**policy_code**|float|Lending Club Loan Stats|sample text|
|**application_type**|object|Lending Club Loan Stats|sample text|
|**annual_inc_joint**|float|Lending Club Loan Stats|sample text|
|**dti_joint**|float|Lending Club Loan Stats|sample text|
|**verification_status_joint**|object|Lending Club Loan Stats|sample text|
|**acc_now_delinq**|float|Lending Club Loan Stats|sample text|
|**tot_coll_amt**|float|Lending Club Loan Stats|sample text|
|**tot_cur_bal**|float|Lending Club Loan Stats|sample text|
|**open_acc_6m**|float|Lending Club Loan Stats|sample text|
|**open_act_il**|float|Lending Club Loan Stats|sample text|
|**open_il_12m**|float|Lending Club Loan Stats|sample text|
|**open_il_24m**|float|Lending Club Loan Stats|sample text|
|**mths_since_rcnt_il**|float|Lending Club Loan Stats|sample text|
|**total_bal_il**|float|Lending Club Loan Stats|sample text|
|**il_util**|float|Lending Club Loan Stats|sample text|
|**open_rv_12m**|float|Lending Club Loan Stats|sample text|
|**open_rv_24m**|float|Lending Club Loan Stats|sample text|
|**max_bal_bc**|float|Lending Club Loan Stats|sample text|
|**all_util**|float|Lending Club Loan Stats|sample text|
|**total_rev_hi_lim**|float|Lending Club Loan Stats|sample text|
|**inq_fi**|float|Lending Club Loan Stats|sample text|
|**total_cu_tl**|float|Lending Club Loan Stats|sample text|
|**inq_last_12m**|float|Lending Club Loan Stats|sample text|
|**acc_open_past_24mths**|float|Lending Club Loan Stats|sample text|
|**avg_cur_bal**|float|Lending Club Loan Stats|sample text|
|**bc_open_to_buy**|float|Lending Club Loan Stats|sample text|
|**bc_util**|float|Lending Club Loan Stats|sample text|
|**chargeoff_within_12_mths**|float|Lending Club Loan Stats|sample text|
|**delinq_amnt**|float|Lending Club Loan Stats|sample text|
|**mo_sin_old_il_acct**|float|Lending Club Loan Stats|sample text|
|**mo_sin_old_rev_tl_op**|float|Lending Club Loan Stats|sample text|
|**mo_sin_rcnt_rev_tl_op**|float|Lending Club Loan Stats|sample text|
|**mo_sin_rcnt_tl**|float|Lending Club Loan Stats|sample text|
|**mort_acc**|float|Lending Club Loan Stats|sample text|
|**mths_since_recent_bc**|float|Lending Club Loan Stats|sample text|
|**mths_since_recent_bc_dlq**|float|Lending Club Loan Stats|sample text|
|**mths_since_recent_inq**|float|Lending Club Loan Stats|sample text|
|**mths_since_recent_revol_delinq**|float|Lending Club Loan Stats|sample text|
|**num_accts_ever_120_pd**|float|Lending Club Loan Stats|sample text|
|**num_actv_bc_tl**|float|Lending Club Loan Stats|sample text|
|**num_actv_rev_tl**|float|Lending Club Loan Stats|sample text|
|**num_bc_sats**|float|Lending Club Loan Stats|sample text|
|**num_bc_tl**|float|Lending Club Loan Stats|sample text|
|**num_il_tl**|float|Lending Club Loan Stats|sample text|
|**num_op_rev_tl**|float|Lending Club Loan Stats|sample text|
|**num_rev_accts**|float|Lending Club Loan Stats|sample text|
|**num_rev_tl_bal_gt_0**|float|Lending Club Loan Stats|sample text|
|**num_sats**|float|Lending Club Loan Stats|sample text|
|**num_tl_120dpd_2m**|float|Lending Club Loan Stats|sample text|
|**num_tl_30dpd**|float|Lending Club Loan Stats|sample text|
|**num_tl_90g_dpd_24m**|float|Lending Club Loan Stats|sample text|
|**num_tl_op_past_12m**|float|Lending Club Loan Stats|sample text|
|**pct_tl_nvr_dlq**|float|Lending Club Loan Stats|sample text|
|**percent_bc_gt_75**|float|Lending Club Loan Stats|sample text|
|**pub_rec_bankruptcies**|float|Lending Club Loan Stats|sample text|
|**tax_liens**|float|Lending Club Loan Stats|sample text|
|**tot_hi_cred_lim**|float|Lending Club Loan Stats|sample text|
|**total_bal_ex_mort**|float|Lending Club Loan Stats|sample text|
|**total_bc_limit**|float|Lending Club Loan Stats|sample text|
|**total_il_high_credit_limit**|float|Lending Club Loan Stats|sample text|
|**revol_bal_joint**|float|Lending Club Loan Stats|sample text|
|**sec_app_fico_range_low**|float|Lending Club Loan Stats|sample text|
|**sec_app_fico_range_high**|float|Lending Club Loan Stats|sample text|
|**sec_app_earliest_cr_line**|object|Lending Club Loan Stats|sample text|
|**sec_app_inq_last_6mths**|float|Lending Club Loan Stats|sample text|
|**sec_app_mort_acc**|float|Lending Club Loan Stats|sample text|
|**sec_app_open_acc**|float|Lending Club Loan Stats|sample text|
|**sec_app_revol_util**|float|Lending Club Loan Stats|sample text|
|**sec_app_open_act_il**|float|Lending Club Loan Stats|sample text|
|**sec_app_num_rev_accts**|float|Lending Club Loan Stats|sample text|
|**sec_app_chargeoff_within_12_mths**|float|Lending Club Loan Stats|sample text|
|**sec_app_collections_12_mths_ex_med**|float|Lending Club Loan Stats|sample text|
|**sec_app_mths_since_last_major_derog**|float|Lending Club Loan Stats|sample text|
|**hardship_flag**|object|Lending Club Loan Stats|sample text|
|**hardship_type**|object|Lending Club Loan Stats|sample text|
|**hardship_reason**|object|Lending Club Loan Stats|sample text|
|**hardship_status**|object|Lending Club Loan Stats|sample text|
|**deferral_term**|float|Lending Club Loan Stats|sample text|
|**hardship_amount**|float|Lending Club Loan Stats|sample text|
|**hardship_start_date**|object|Lending Club Loan Stats|sample text|
|**hardship_end_date**|object|Lending Club Loan Stats|sample text|
|**payment_plan_start_date**|object|Lending Club Loan Stats|sample text|
|**hardship_length**|float|Lending Club Loan Stats|sample text|
|**hardship_dpd**|float|Lending Club Loan Stats|sample text|
|**hardship_loan_status**|object|Lending Club Loan Stats|sample text|
|**orig_projected_additional_accrued_interest**|float|Lending Club Loan Stats|sample text|
|**hardship_payoff_balance_amount**|float|Lending Club Loan Stats|sample text|
|**hardship_last_payment_amount**|float|Lending Club Loan Stats|sample text|
|**debt_settlement_flag**|object|Lending Club Loan Stats|sample text|
|**debt_settlement_flag_date**|object|Lending Club Loan Stats|sample text|
|**settlement_status**|object|Lending Club Loan Stats|sample text|
|**settlement_date**|object|Lending Club Loan Stats|sample text|
|**settlement_amount**|float|Lending Club Loan Stats|sample text|
|**settlement_percentage**|float|Lending Club Loan Stats|sample text|
|**settlement_term**|float|Lending Club Loan Stats|sample text|