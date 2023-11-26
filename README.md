# FreeEigen

## Overview

FreeEigen is a Jupyter Notebook designed to plot the eigenspectrum of free lattice fermions. The eigenvalues are computed using numpy's `np.linalg.eig` function.

FreeEigenは、自由格子フェルミオンの固有スペクトルをプロットするために設計されたJupyter Notebookです。固有値はnumpyの`np.linalg.eig`関数を使用して計算されます。


## Current Status 現在の状況(2023/11/26)

The project currently includes two distinct classes along with a lookup table for trigonometric functions. 

`LatticeFermion` serves as the master class for fermions, covering various types including naive, Wilson, and Ginsparg-Wilson (GW) fermions.

このプロジェクトには、現在、2つの異なるクラスと三角関数のルックアップテーブルが含まれています。

`LatticeFermion`は、ナイーブ、ウィルソン、ギンスパーグ-ウィルソン（GW）フェルミオンを含む様々なタイプをカバーするフェルミオンのマスタークラスです。

## To Do 予定 

- **Extend the Mass Parameter:** Further development to incorporate variable mass parameters.
  
- **質量：** 質量パラメータを取り入れるためのさらなる開発。
  
- **Multithreading Implementation:** As of 2023/11/26, multithreading capabilities are not yet implemented and are planned for future updates.
  
- **マルチスレッドの実装：** 2023年11月26日現在、マルチスレッド機能はまだ実装されておらず、今後のアップデートで計画されています。

  
## Not to Do

- **Gauge Action Implementation:** The project does not intend to implement the gauge action.
  
- **ゲージアクションの実装：** このプロジェクトはゲージアクションの実装を予定はありません。


## Acknowledgments
Special thanks to:
- [NatLee]
- [Hsu]
- [Ken]
  
  whom providing the techique support to this work when I've no idea about python.
  
  彼らは、私がPythonについて何も知らないときに、この作業に技術的なサポートを提供してくれました。
