{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "c5cabbd7-17d8-4b5a-aab7-edaebfadf1ed",
   "metadata": {},
   "outputs": [],
   "source": [
    "import numpy as np"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "ca8bf6a7-a82e-42b5-b1da-b837fce7a96c",
   "metadata": {},
   "outputs": [],
   "source": [
    "ones_arr = np.ones((5,5),dtype=int)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "0252aad8-97cf-4d8f-b996-4f26e94472ac",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "array([[1, 1, 1, 1, 1],\n",
       "       [1, 1, 1, 1, 1],\n",
       "       [1, 1, 1, 1, 1],\n",
       "       [1, 1, 1, 1, 1],\n",
       "       [1, 1, 1, 1, 1]])"
      ]
     },
     "execution_count": 3,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "ones_arr"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "e6f322d4-e409-49f4-b377-f5d0c9de8f0e",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "array([[255, 255, 255, 255, 255],\n",
       "       [255, 255, 255, 255, 255],\n",
       "       [255, 255, 255, 255, 255],\n",
       "       [255, 255, 255, 255, 255],\n",
       "       [255, 255, 255, 255, 255]])"
      ]
     },
     "execution_count": 4,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "ones_arr * 255"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "966d000b-afd6-4913-ac10-5542a41a09a2",
   "metadata": {},
   "outputs": [],
   "source": [
    "import matplotlib.pyplot as plt"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "5e3d9df8-7ae9-424f-bc63-a302180524ca",
   "metadata": {},
   "outputs": [],
   "source": [
    "matplotlib inline"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "2416d196-fe44-46c4-b15b-6d03b5f19afb",
   "metadata": {},
   "outputs": [],
   "source": [
    "from PIL import Image # python imaging library "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "51b003e2-0bc8-48c8-9fab-6ff8b8c5a1ab",
   "metadata": {
    "scrolled": true
   },
   "outputs": [],
   "source": [
    "#horse_img = Image.open('C:\\Users\\A3MAX SOFTWARE TECH\\Desktop\\WORK\\1. KODI WORK\\1. NARESH\\10. WORKSHOP\\8. Exploring Generative AI through computer vision\\horse1.jpg')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "eb0466da-7088-485b-a90b-0f30a7a41772",
   "metadata": {},
   "outputs": [],
   "source": [
    "horse_img = Image.open(r'C:\\Users\\A3MAX SOFTWARE TECH\\Desktop\\WORK\\1. KODI WORK\\1. NARESH\\10. WORKSHOP\\7. Exploring Generative AI through computer vision\\horse1.jpg')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "cdb64978-b637-493c-83c7-7938690ff646",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "image/jpeg": 
  
