
# An Efficient Nonlinear Precoder for the MU-MIMO with 1bit DACs.

Source files for our recent published paper: Efficient Nonlinear Precoding for Massive MU-MIMO Downlink Systems with 1-Bit DACs;  If you use our codes, please cite our paper.

%% developed by Lei Chu and Fei Wen


%% main simulation file for our published paper: Efficient Nonlinear Precoding for Massive MU-MIMO Downlink Systems with 1-Bit DACs; 

## Notes:

(1)  Our simulation platform is revised from the basic MIMO platform provided by "Quantized Precoding for Massive MU-MIMO", which is available at https://github.com/quantizedmassivemimo/1bit\_precoding; We have updated the proposed precoder (ADMM\_Leo--v2.m); Interested readers can directly add the file (ADMM\_Leo--v2.m) into the well established simulator \cite{Jacobsson2016Quantized} for performance comparison; The lastest version of the proposed precoder can support MU-MIMO with multi-bit DACs; We are greatly appreciated for the authors in \cite{Jacobsson2016Quantized} for their selfless spirit. Specially, they provided fundamental simulation platform and benchmark precoders (i.e., MRT, ZF, WF, SDR and SQUID). 


(2)  If SDR-based precoders are employed for comparasion, you should establish CVX which is avaliable at http://cvxr.com/cvx/;

(3)  If you use our codes, please cite our paper; 
Chu L, Wen F, Li L, et al. Efficient Nonlinear Precoding for Massive MU-MIMO Downlink Systems with 1-Bit DACs[J]. 2018. Avaliable at  https://arxiv.org/abs/1804.08839;

(4) If you get any question for our codes, please contact: leochu@sjtu.edu.cn;

(5)  We are appreciated for Dr. Studer from Cornell University for the discussions for setting the paramters in SQUID preocder in the case of small size MU-MIMO. 


