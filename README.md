Download Link: https://assignmentchef.com/product/solved-ee6203-assignment-1
<br>
<ol>

 <li>A system is described by the following difference equation</li>

</ol>

c k(  3) 3 (c k 2) 5 (c k 1) 7 ( )c k  9 ( )u k

where the output y k( ) c k( ). Define the state variables as

x k<sub>1</sub>( )  c k x k( ); <sub>2</sub>( )  c k( 1);x k<sub>3</sub>( )  c k(  2)

Obtain a state-space representation for the system.

<ol start="2">

 <li>Consider the two systems connected as shown below.</li>

</ol>

The respective state-space representations are given as follow:

System S<sub>1 </sub>:

0.1 (u k 1) 0.2 ( )u k  0.3 ( )e k

System S<sub>2 </sub>:




x k<sub>1</sub>( 1) 0.4 0.5x k<sub>1</sub>( ) 0.8

                                u k( )

x k<sub>2</sub>( 1) 0.6 0.7x k<sub>2</sub>( ) 0.9

x k<sub>1</sub>( )

( )y k 1 2<sub>       </sub>

x k<sub>2</sub>( )

If x k<sub>3</sub>( ) u k( ), give a state-space representation for the overall system,

x k<sub>1</sub>( )

       

x(k 1) Ax( )k Be k( );     x( )k <sup></sup>x k<sub>2</sub>( )<sub>  </sub>

x k<sub>3</sub>( )

( )y k Cx( )k de k ( )




<ol start="3">

 <li>Given the state equation of a linear system as</li>

</ol>



x( )t Ax( )t Bu t( )

The ZOH equivalent, with a sampling period of T seconds, is of the following form:

x(k 1) A x<sub>d </sub>( )k B<sub>d</sub>u k( )




If

 0    1        0

A4 5;B  1 ;T  0.5 sec

(i)  Find  A<sub>d</sub> and  B<sub>d </sub>.

X( )z (ii) Find the transfer function  .

U z( )

(iii) Determine the characteristic equation of the discretised system and obtain           the eigenvalues of A<sub>d </sub>.




<ol start="4">

 <li>A discrete-time system is given by</li>

</ol>




1  2         3

x(k 1)      x( )k  u k( )

1  2         4

( )y k 5 6x( )k




<ul>

 <li>Determine a co-ordinate transformation, i.e. find Q in the following</li>

</ul>




w<sub>Q</sub>( )k =Q x<sup>1 </sup>( )k




that transforms the system into the observable canonical form (OCF). Hence, using Q,  determine a state-space representation which is in the OCF form.




<ul>

 <li>Determine a co-ordinate transformation, i.e. find P in the following</li>

</ul>




w<sub>P</sub>( )k =P x<sup>1 </sup>( )k




that transforms the system into the controllable canonical form (CCF). Hence, using P,  determine a state-space representation which is in the CCF form.




<ol start="5">

 <li>A continuous-time system is as shown below. Let M  625,K<sub>S </sub>10.</li>

</ol>

<ul>

 <li>Obtain a state-space representation for the continuous-time system with the state variables as indicated and the output variable y t( )  x t<sub>1</sub>( ).</li>

 <li>The system is sampled with a zero-order hold and the sampling period is 0.5 second. Obtain a zero-order hold equivalent of the continuous-time system.</li>

</ul>




<ul>

 <li>Find the deadbeat control law of the following form u k( ) Kx( )k</li>

</ul>

Show that the response is indeed deadbeat.


