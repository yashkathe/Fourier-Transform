# Section 2

## Computational Foundations of the Fourier Transform

![1](../readme_content/2/1)

## Complex Numbers

![3](../readme_content/2/3)

The idea of complex numbers is to extend the framework of number line from a 1-D
line to 2-D plane

![2](../readme_content/2/2)

-> Complex Numbers and the imaginary opearator are very useful for applications
in signal processing, engineering etc

The reason why complex numbers are so useful is that they pack a lot of
information into a very compact representation

- The Fourier transform returns complex numbers and you take the magnitude or
  the distance of the complex Fourier coefficient away from the origin and that
  is taken to be the amplitude at some frequency. And the angle with respect to
  the positive real axis is going to be the phase at that frequency.

### Calculate magnitude of Complex Numbers

#### Method 1: Creating a right angled triangle

![4](../readme_content/2/4)

#### Method 2: Take complex conjugate of complex number

![5](../readme_content/2/5)

Conjugate of complex number is the number with the sign og imaginary part
flipped

---

### Calculating Angle of a Complex Number

![6](../readme_content/2/6)

## Euler's Formula

![7](../readme_content/2/7)

## Sine Waves and Complex Sine Waves

![8](../readme_content/2/8)

### Sine Waves Properties

Amplitude, Frequency and Phase are independent of each other, meaning that none
of the features determines any of the other features.

#### 1. Frequency

![9](../readme_content/2/9)

When the sine waves are **measured in time** and we're dealing with sinewaves
from the periodicity of minutes or seconds, then we use the unit of **Hertz**

**Hertz is the reciprocal of time**

Sine wave at one hertz repeats itself once every second

A five hertz sine wave means five cycles per second or one cycle every 200
milliseconds.

#### 2. Phase

![13](../readme_content/2/13)

Phase is quantified as the value of the sine wave as it crosses the point
corresponding to time equals zero.

Phase is a **circular measure** because it doesn't necessarily go negative to
positive or left and right, it goes around in a circle.

Two of the most important phases for sine waves are zero and pi by two. These
two phases define what are commonly called a **sine wave** and a **cosine
wave**.

Sine and Cosine is that they are **orthogonal**

#### 3. Amplitude

![10](../readme_content/2/10)

Amplitude refers to the total height over the entire signal, and that's actually
quantified as the **distance between zero and the peak**

## Complex Sine Wave

![11](../readme_content/2/11)

It's a time series.  
It has time, it has a real part and an imaginary part. So it's actually a
function that lives in three dimensions

## Dot Product

The dot product is a single number that tells you about the relationship between
two vectors, where a vector is a list of numbers.

### How to compute dot product ?

![12](../readme_content/2/12)

1. You line up the two vectors check whether they have the same number of
   elements
2. And then you multiply each of the corresponding pairs of numbers.
