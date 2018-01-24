---
layout: post
title: [ISL Study] 6. Linear Model Selection and Regularization
date: 2018-01-24 13:57:00
categories: study
tags: ml
---

$\def\ddd{\cdots}\def\vsum{\sum\limits}\def\ttt{\therefore}\def\www{\because}\def\ra{\rightarrow}\def\an{\infty}\def\d{\delta}\def\xx{\mathbf{x}}\def\mb#1{\mathbf{#1}}\def\tr{\text{tr}}\def\ee{\boldsymbol{\epsilon}}\def\a{\alpha}\def\b{\beta}\def\e{\epsilon}\def\g{\gamma}\def\m{\mu}\def\cd{\cdot}\def\fe{\fallingdotseq}\def\p{\phi}\def\s{\sigma}\def\yy{\mathbf{y}}\def\mm{\boldsymbol{\mu}}\def\bb{\boldsymbol{\beta}}\def\mq{\mathbf{q}}\def\ns{\varnothing}\def\t{\times}\def\l{\lambda}$ 

반응변수 $Y$와 설명변수 $X_{1},X_{2},\ddd ,X_{p}$사이의 상관관계를 설명하기위해, 우리는 다음과 같이 가장 쉽고 간단하다고 할 수 있는 선형회귀모형을 사용했었다.

\begin{equation}

Y=\b_{0}+\b_{1}X_{1}+\ddd+\b_{p}X_{p}+\e

\end{equation}



$$Y=\b_{0}+\b_{1}X_{1}+\ddd+\b_{p}X_{p}+\e​$$

3장에서 보았듯이 이러한 모형은 보통 최소제곱법을 사용하여 적합한다.