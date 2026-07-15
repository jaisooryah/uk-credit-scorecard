# Feature Dictionary

After WoE binning and pruning, **33 features** survived (IV >= 0.02, excluding Lending Club's own grading columns to force the model to learn from underlying data).

## Information Value strength brackets

| Bracket | IV range | Meaning |
|---|---|---|
| Strong | > 0.3 | Highly predictive |
| Medium | 0.1 - 0.3 | Solid |
| Weak | 0.02 - 0.1 | Marginal but usable |
| Dropped | < 0.02 | Uninformative — removed |

## Features ranked by IV

| Rank | Feature | IV | Strength |
|---|---|---|---|
| 1 | `term` | 0.1649 | Medium |
| 2 | `fico_range_high` | 0.1109 | Medium |
| 3 | `dti` | 0.0654 | Weak |
| 4 | `acc_open_past_24mths` | 0.0585 | Weak |
| 5 | `avg_cur_bal` | 0.0544 | Weak |
| 6 | `bc_open_to_buy` | 0.0512 | Weak |
| 7 | `verification_status` | 0.0505 | Weak |
| 8 | `tot_hi_cred_lim` | 0.0493 | Weak |
| 9 | `num_tl_op_past_12m` | 0.0425 | Weak |
| 10 | `tot_cur_bal` | 0.0404 | Weak |
| 11 | `total_bc_limit` | 0.0368 | Weak |
| 12 | `mths_since_recent_inq` | 0.0343 | Weak |
| 13 | `num_actv_rev_tl` | 0.0330 | Weak |
| 14 | `all_util` | 0.0317 | Weak |
| 15 | `num_rev_tl_bal_gt_0` | 0.0313 | Weak |
| 16 | `funded_amnt` | 0.0307 | Weak |
| 17 | `home_ownership` | 0.0307 | Weak |
| 18 | `loan_amnt` | 0.0307 | Weak |
| 19 | `mort_acc` | 0.0305 | Weak |
| 20 | `funded_amnt_inv` | 0.0299 | Weak |
| 21 | `annual_inc` | 0.0293 | Weak |
| 22 | `open_rv_24m` | 0.0278 | Weak |
| 23 | `total_rev_hi_lim` | 0.0277 | Weak |
| 24 | `mo_sin_rcnt_tl` | 0.0271 | Weak |
| 25 | `mths_since_recent_bc` | 0.0270 | Weak |
| 26 | `bc_util` | 0.0265 | Weak |
| 27 | `percent_bc_gt_75` | 0.0255 | Weak |
| 28 | `installment` | 0.0255 | Weak |
| 29 | `mo_sin_rcnt_rev_tl_op` | 0.0248 | Weak |
| 30 | `mo_sin_old_rev_tl_op` | 0.0231 | Weak |
| 31 | `revol_util` | 0.0230 | Weak |
| 32 | `purpose` | 0.0206 | Weak |
| 33 | `inq_last_12m` | 0.0202 | Weak |