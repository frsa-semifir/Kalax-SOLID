 #   S O L I D   a v e c   J a v a 
 
 # #   P r � s e n t a t i o n 
 L o r s   d u   d � v e l o p p e m e n t   d ' u n   p r o j e t   i n f o r m a t i q u e   a v e c   d e s   l a n g u a g e   u t i l i s a n t   l e   p a r a d i g m e   d e   l a   p r o g r a m m a t i o n   o r i e n t � e   o b j e t   n o u s   d e v o n s   r � f l � c h i r   c o m m e n t   a g e n c e r   n o t r e   c o d e   p o u r   q u ' i l   s o i t   ` r � s i l l i a n t ` ,   ` � v o l u t i f `   e t   f a c i l e   a   m a i n t e n i r . 
 
 L a   s t r u c t u r e   d e   c o d e   S O L I D   d � f i n i e   u n   c e r t a i n   n o m b r e   d e   p r � c e p t e s   q u i   p e r m e t t e n t   d ' a v o i r   u n   c o d e   m i e u x   s t r u c t u r � . 
 
 # #   Q u ' e s t - c e   q u e   l e   S O L I D 
 
 S O L I D   e s t   u n   a c r o n y m e   d e   5   p r i n c i p e s   q u i   s o n t   l i �   l e s   u n   a u x   a u t r e s . 
 
 # # #   S i n g l e   r e s p o n s i b i l i t y   p r i n c i p l e :   
 
 U n e   c l a s s e ,   u n e   [ f o n c t i o n ] ( L e x i q u e . m d # f o n c t i o n )   o u   u n e   [ m � t h o d e ] ( L e x i q u e . m d # m � t h o d e - )   d o i t   a v o i r   u n e   e t   u n e   s e u l e   [ r e s p o n s a b i l i t � ] ( L e x i q u e . m d # r e s p o n s a b i l i t � - ) . 
 
 # # #   O p e n / c l o s e d   p r i n c i p l e :   
 U n e   [ e n t i t �   a p p l i c a t i v e ] ( L e x i q u e . m d # e n t i t � s - a p p l i c a t i v e - )   d o i t   � t r e   f e r m � e   �   l a   [ m o d i f i c a t i o n ] ( L e x i q u e . m d # m o d i f i c a t i o n - )   d i r e c t e   m a i s   o u v e r t e   �   l ' [ e x t e n s i o n ] ( L e x i q u e . m d # e x t e n s i o n - ) . 
 
 # # #   L i s k o v   s u b s t i t u t i o n   p r i n c i p l e :   
 U n e   [ i n s t a n c e ] ( L e x i q u e . m d # i n s t a n c e - )   d e   [ t y p e ] ( L e x i q u e . m d # t y p e - )   T   d o i t   p o u v o i r   � t r e   r e m p l a c � e   p a r   u n e   [ i n s t a n c e ] ( L e x i q u e . m d # i n s t a n c e - )   d e   [ t y p e ] ( L e x i q u e . m d # t y p e - )   G ,   t e l   q u e   G   [ s o u s - t y p e ] ( L e x i q u e . m d # s o u s - t y p e - )   d e   T ,   s a n s   q u e   c e l a   n e   m o d i f i e   l a   [ c o h � r e n c e ] ( L e x i q u e . m d # c o h r e n c e - )   d u   p r o g r a m m e . 
 
 # # #   I n t e r f a c e   s e g r e g a t i o n   p r i n c i p l e : 
 P r � f � r e r   p l u s i e u r s   [ i n t e r f a c e s   s p � c i f i q u e s ] ( L e x i q u e . m d # i n t e r f a c e s - s p c i f i q u e s - )   p o u r   c h a q u e   c l i e n t   p l u t � t   q u ' u n e   s e u l e   [ i n t e r f a c e   g � n � r a l e ] ( L e x i q u e . m d ) . 
 
 # # #   D e p e n d e n c y   i n v e r s i o n   p r i n c i p l e : 
 i l   f a u t   d � p e n d r e   d e s   [ a b s t r a c t i o n s ] ( L e x i q u e . m d # a b s t r a c t i o n s - ) ,   p a s   d e s   [ i m p l � m e n t a t i o n s ] ( L e x i q u e . m d # i m p l � m e n t a t i o n s - ) . 
 
 # #   L e   K a l a x   d ' I K E A 
 ` ` ` 
 L e   m e u b l e   K a l a x   d ' I K E A   e s t   u n e   b o n n e   m � t a p h o r e   d e s   p r i n c i p e s   S O L I D .   
 ` ` ` 
 C i t a t i o n   d e   _ B e n o i t   R o u t i e r _ . 
 
 N o u s   a l l o n s   v o i r   l e s   p r i n c i p e s   S O L I D   a v e c   l e   m e u b l e   K a l a x   d ' I K E A . 
 
 # # #   S i n g l e   r e s p o n s i b i l i t y   p r i n c i p l e : 
 L a   [ r e s p o n s a b i l i t � ] ( L e x i q u e . m d )   d e   c e   m e u b l e   e s t   d e   p o u v o i r   a g e n c e r   d e s   c o m p o s a n t s   e n s e m b l e .   
 * * C ' e s t   s a   s e u l e   [ r e s p o n s a b i l i t � ] ( L e x i q u e . m d ) * * . 
 
 I l   p e u t   c o n t e n i r   p l u s i e u r s   e m p l a c e m e n t s   q u i   a u r o n t   c h a c u n   l e u r s   p r o p r e s   [ r e s p o n s a b i l i t � ] ( L e x i q u e . m d ) s   ( t i r o i r ,   p l a c a r d ,   b a c ,   e t c . ) . 
 
 G r � c e   �   c e   p r i n c i p e ,   c e   m e u b l e   e s t   f a c i l e   �   u t i l i s e r   e t   �   p l a c e r   d a n s   b e a u c o u p   d e   s i t u a t i o n s . 
 
 L e   p r i n c i p e   d e   [ r e s p o n s a b i l i t �   u n i q u e ] ( # _ _ s i n g l e - r e s p o n s i b i l i t y - p r i n c i p l e _ _ - )   p e r m e t   l a   r � u t i l i s a t i o n   e t   l a   s i m p l i f i c a t i o n   d e s   [ e n t i t � s   a p p l i c a t i v e s ] ( L e x i q u e . m d # e n t i t � s - a p p l i c a t i v e - ) . 
 
 # # #   O p e n / C l o s e   p r i n c i p l e : 
 I l   e s t   p o s s i b l e   d e   c h a n g e r   c e   q u e   l ' o n   p e u t   f a i r e   a v e c   c e   m e u b l e   e n   a j o u t a n t   d e s   e m p l a c e m e n t s , 
 e n   c o l l a n t   u n   a u t r e   m e u b l e   o u   e n   c h a n g e a n t   l e s   e m p l a c e m e n t s   m a i s   s a n s   a v o i r   �   m o d i f i e r   l e   m e u b l e 
 e n   l u i - m � m e . 
 
 L e   K a l a x   e s t   o u v e r t   �   l ' e x t e n s i o n   m a i s   f e r m �   �   l a   m o d i f i c a t i o n . 
 
 L e   p r i n c i p e   d ' [ o u v e r t / f e r m � ] ( # _ _ o p e n c l o s e d - p r i n c i p l e _ _ - )   p e r m e t   d e   n e   p a s   a v o i r   �   m o d i f i e r   u n e   e n t i t �   a p p l i c a t i v e   q u i   e s t   d � j �   f o n c t i o n n e l   m a i s   d e   p o u v o i r   f a c i l e m e n t   c r � e r   d e s   e x t e n s i o n s .   C o m m e   l e   p r e m i e r   p o i n t ,   i l   e s t   p l u s   f a c i l e   a i n s i   d e   r � u t i l i s e r   d u   c o d e   d � j �   f o n c t i o n n e l   e t   i l   e s t   p l u s   f a c i l e   d e   l e   f a i r e   � v o l u e r . 
 
 # # #   L i s k o v   s u b s t i t u t i o n   p r i n c i p l e : 
 L e s   e m p l a c e m e n t s   d ' u n   m e u b l e   K a l a x   p e r m e t t e n t   d e   f a c i l e m e n t   i n t e r c h a n g e r   l e s   c o m p o s a n t s   q u e   l ' o n   p e u t   m e t t r e   �   l ' i n t � r i e u r .   I l s   r e s p e c t e n t   t o u s   l e s   m � m e   d i m e n s i o n s . 
 
 L e s   c o m p o s a n t s   q u e   l ' o n   p e u t   y   i n s � r e r   r e s p e c t e n t   e u x   a u s s i   l e s   m � m e s   d i m e n s i o n s .   I l   e s t   d o n c   f a c i l e   d e   l e s   i n t e r c h a n g e r . 
 
 D a n s   l e   p r e m i e r   e m p l a c e m e n t   n o u s   p o u v o n s   m e t t r e   : 
 *   D e u x   t i r o i r s   l ' u n   s u r   l ' a u t r e   q u i   f o r m e   �   e u x   d e u x   u n   c u b e   r e s p e c t a n t   l e s   d i m e n s i o n s   d ' u n   e m p l a c e m e n t   K a l a x . 
 *   U n e   b o i t e   e n   t i s s u   a y a n t   r e s p e c t a n t   l e s   b o n n e s   d i m e n s i o n s . 
 *   U n e   b o i t e   e n   p l a s t i q u e   a y a n t   d i v e r s   c o u l e u r s . 
 *   U n   c o f f r e . 
 *   U n   e m p l a c e m e n t   v i d e .   
 *   N o t r e   p r o p r e   [ t y p e ] ( L e x i q u e . m d # t y p e - )   d e   c o m p o s a n t   t a n t   q u ' i l   r e s p e c t e   l e s   d i m e n s i o n s   d ' u n   e m p l a c e m e n t   K a l a x . 
 
 T o u t   c o m p o s a n t s   d ' e m p l a c e m e n t   d ' u n   K a l a x   p o s s � d a n t   l e s   b o n n e s   d i m e n s i o n s   p e u t   � t r e   m i s   d a n s   u n   e m p l a c e m e n t . 
 
 A i n s i ,   l e   m e u b l e   e n   l u i - m � m e   a   s a   p r o p r e   [ r e s p o n s a b i l i t � ] ( L e x i q u e . m d # r e s p o n s a b i l i t � - )   e t   c h a q u e   e m p l a c e m e n t   d � f i n i e   s a   p r o p r e   [ r e s p o n s a b i l i t � ] ( . / L e x i q u e . m d # r e s p o n s a b i l i t � - ) . 
 
 I l   r e s p e c t e   l e   p r i n c i p e   d e   s u b s t i t u t i o n   d e   L i s k o v   c e   q u i   l u i   p e r m e t   d ' � t r e   u n   m e u b l e   f o r t e m e n t   m o d u l a b l e   e t   d o n c   u t i l i s a b l e   d a n s   d e   n o m b r e u x   c a s . 
 
 C e   p r i n c i p e   d i t   q u ' u n e   e n t i t �   a p p l i c a t i v e   d e   [ t y p e ] ( L e x i q u e . m d # t y p e - )   ` T `   ( i c i   u n   e m p l a c e m e n t   v i d e )   p e u t   � t r e   r e m p l a c �   p a r   u n e   a u t r e   d e   [ t y p e ] ( L e x i q u e . m d # t y p e - )   ` G `   ( u n   c o m p o s a n t   d ' e m p l a c e m e n t )   s i   ` S `   e s t   u n   s o u s - [ t y p e ] ( L e x i q u e . m d # t y p e - )   d e   ` T `   ( l e   c o m p o s a n t   d ' e m p l a c e m e n t   r e s p e c t e   l e s   d i m e n s i o n s   d ' u n   e m p l a c e m e n t ) . 
 
 # # #   I n t e r f a c e   s e g r e g a t i o n   p r i n c i p l e 
 I l   e x i s t e   u n   g r a n d   n o m b r e   d e   c o m p o s a n t s   d ' e m p l a c e m e n t   p o u r   u n   m e u b l e   K a l a x .   
 C e r t a i n s   s o n t   d e s   b o i t e s ,   d e s   t i r o i r s ,   d e   p l u s   p e t i t s   e m p l a c e m e n t s ,   e t c . 
 M a i s   i l s   s o n t   t o u s   d e s   e m p l a c e m e n t s . 
 
 L e   c o m p o s a n t   b o i t e   e n   t i s s u   a   l e s   c a r a c t � r i s t i q u e s   d ' u n   e m p l a c e m e n t ,   d ' u n   o b j e t   e n   t i s s u   e t   d ' u n e   b o i t e . 
 
 L e   c o m p o s a n t   b o i t e   e n   b o i s   a   l e s   c a r a c t � r i s t i q u e s   d ' u n   e m p l a c e m e n t ,   d ' u n   o b j e t   e n   b o i s   e t   d ' u n e   b o i t e . 
 
 L e   c o m p o s a n t   d o u b l e   t i r o i r   a   l e s   c a r a c t � r i s t i q u e s   d ' u n   e m p l a c e m e n t ,   d ' u n   o b j e t   e n   b o i s   e t   d ' u n   t i r o i r .     
 
 C h a q u e   c o m p o s a n t   a   s e s   p r o p r e s   c a r a c t � r i s t i q u e s   m a i s   o n   r e t r o u v e   c e r t a i n e s   c a r a c t � r i s t i q u e s   c o m m u n e s   �   p l u s i e u r s   c o m p o s a n t s .   
 
 L e   p r i n c i p e   d e   s � g r � g a t i o n   d ' i n t e r f a c e   s t i p u l e   q u ' i l   e s t   p r � f � r a b l e   d e   d � c o u p e r   l e s   i n t e r f a c e s   ( i c i   l i s t e   d e   c a r a c t � r i s t i q u e s )   p l u t � t   q u e   d ' u t i l i s e r   u n e   s e u l e   i n t e r f a c e   p o u r   c h a q u e   e n t i t �   a p p l i c a t i v e .   A i n s i   p o u r   l e   t y p a g e ,   n o u s   p o u v o n s   a s s e m b l e r   d e s   i n t e r f a c e s   e n t r e   e l l e s   e t   r � u t i l i s �   s e s   i n t e r f a c e s   s u r   p l u s i e u r s   [ e n t i t � s   a p p l i c a t i v e s ] ( L e x i q u e . m d # e n t i t � s - a p p l i c a t i v e - ) .   
 
 C e   p r i n c i p e   v a   d e   p a i r   a v e c   l e s   p r i n c i p e s   v u   p r � c � d e m m e n t . 
 
 # # #   D e p e n d e n c y   i n v e r s i o n   p r i n c i p l e : 
 C o m m e   d i t   p r � c � d e m m e n t ,   l e   m e u b l e   K a l a x   n ' a   p a s   d e   c o u p l a g e   f o r t   a v e c   s e s   c o m p o s a n t s .   
 N o u s   p o u v o n s   f a c i l e m e n t   c h a n g e r   d e   c o m p o s a n t   d ' e m p l a c e m e n t   p a r   u n   a u t r e . 
 C e l a   e s t   p o s s i b l e   c a r   l e   m e u b l e   n e   d � f i n i e   q u e   d e s   d i m e n s i o n s   �   r e s p e c t e r   p o u r   q u ' u n   c o m p o s a n t   p u i s s e   � t r e   u t i l i s �   d a n s   u n   e m p l a c e m e n t . 
 
 N o u s   s t o c k o n s   d e s   c o m p o s a n t s   s o u s   l a   f o r m e   a b s t r a i t e   d ' e m p l a c e m e n t . 
 C h a q u e   c o m p o s a n t   e s t   u n e   [ i m p l � m e n t a t i o n ] ( L e x i q u e . m d # i m p l � m e n t a t i o n s - )   ( m i s e   e n   p r a t i q u e   c o n c r � t e )   d ' u n   e m p l a c e m e n t   ( q u i   r e s t e   a b s t r a i t ) . 
 
 C e   p r i n c i p e   s t i p u l e   q u e   n o u s   n e   d e v o n s   p a s   u t i l i s e r   d i r e c t e m e n t   d ' [ i m p l � m e n t a t i o n ] ( L e x i q u e . m d # i m p l � m e n t a t i o n s - ) s   p o u r   l e   t y p a g e   m a i s   p l u t � t   d e s   a b s t r a c t i o n s .   
 
 I l   v i e n t   a v e c   l a   n o t i o n   d e   c o u p l a g e   f o r t   e t   f a i b l e . 
 
 S i   u n   m e u b l e   n e   p e u t   p r o p o s e   p a s   d ' e m p l a c e m e n t   s t a n d a r d   m a i s   o b l i g e   l ' u t i l i s a t i o n   d ' u n   c e r t a i n   c o m p o s a n t   ( c e   q u i   r e v i e n t   �   t y p e r   a v e c   u n e   [ i m p l � m e n t a t i o n ] ( L e x i q u e . m d # i m p l � m e n t a t i o n s - ) )   l o r s   i l   y   a   u n   l i e n   f o r t   e n t r e   l e   m e u b l e   e t   s o n   c o m p o s a n t .   O n   p a r l e   a l o r s   d e   c o u p l a g e   f o r t . 
 L ' h � r i t a g e   o u   l e   t y p a g e   p a r   c l a s s e   f o r m e   u n   c o u p l a g e   f o r t   q u i   r e n d   p l u s   r i g i d e   e t   m o i n s   a d a p t a t i f   n o t r e   c o d e . 
 
 A   c o n t r a r i o ,   s i   l e   m e u b l e   p r o p o s e   j u s t e   d e s   e m p l a c e m e n t s   s t a n d a r d i s �   q u i   n e   f o r c e   p a s   l ' u t i l i s a t i o n 
 d ' u n   c o m p o s a n t   s p � c i f i q u e ,   c e l a   l e   r e n d   p l u s   m o d u l a b l e   e t   a d a p t a t i f   a u x   d i f f � r e n t s   b e s o i n s . 
 O n   d � f a i t   l e   l i e n   f o r t   e n t r e   l e s   d e u x   e n t i t � s .   
 O n   p a r l e   a l o r s   d e   c o u p l a g e   f a i b l e . 
 L ' u t i l i s a t i o n   d ' i n t e r f a c e s   p o u r   l e   t y p a g e   p e r m e t   l a   c r � a t i o n   d e   c o u p l a g e   f a i b l e . 
 
 I l   e s t   e n   g � n � r a l   p r � f � r a b l e   d ' u t i l i s e r   u n   c o u p l a g e   f a i b l e   p l u t � t   q u e   f o r t   d a n s   n o t r e   c o d e . 
 
 # #   N o t i o n s   p r o c h e s   d e   S O L I D 
 
 # # #   I O D   ( I n j e c t i o n   o f   d e p e n d e n c i e s ) 
 L e   p r i n c i p e   d ' i n j e c t i o n   d e   d � p e n d a n c e s   e s t   u n e   e x t e n s i o n   d e s   p r i n c i p e s   S O L I D . 
 
 N o t r e   m e u b l e   n e   d � f i n i t   a u c u n   c o m p o s a n t   d e j a   m i s   e n   p l a c e .   
 I l   n e   d � f i n i t   q u ' u n   c e r t a i n   n o m b r e   d ' e m p l a c e m e n t s   d i s p o n i b l e s   o �   n o u s   p o u v o n s   ` i n j e c t e r `   d e s   c o m p o s a n t s   e n   [ f o n c t i o n ] ( L e x i q u e . m d # f o n c t i o n )   d e s   b e s o i n s .   
 
 C ' e s t   c a   l e   p r i n c i p e   d ' i n j e c t i o n   d e   d � p e n d a n c e s .   
 N e   p a s   d � f i n i r   l e s   a t t r i b u t s   d ' u n e   c l a s s e   d a n s   c e l l e - c i   m a i s   p l u t � t   d e   p o u v o i r   y   i n j e c t e r   n o s   [ i n s t a n c e ] ( L e x i q u e . m d # i n s t a n c e - ) s   a u   b e s o i n . 
 
 L ' i n j e c t i o n   d e   d � p e n d a n c e s   e s t   u n   p r i n c i p e   i m p o r t a n t   p o u r   l a   s t r u c t u r a t i o n   d ' u n   p r o g r a m m e   c a r   i l   p e r m e t   u n e   p l u s   g r a n d e   m o d u l a r i t �   e t   l e   r e n d   p l u s   a d a p t a t i f   a u x   b e s o i n s   e t   a u x   � v o l u t i o n s   f u t u r e s . 
 
 L ' I O D   e t   S O L I D   v o n t   s o u v e n t   d e   p a i r . 
 
 S p r i n g   e s t   u n   f r a m e w o r k   J a v a   p e r m e t t a n t   l a   m i s e   e n   p l a c e   d ' I n v e r s i o n   d e   C o n t r o l   ( f a i t   q u e   c e   s o i t   l e   f r a m e w o r k   q u i   a s s e m b l e   n o s   [ e n t i t � s   a p p l i c a t i v e s ] ( L e x i q u e . m d # e n t i t � s - a p p l i c a t i v e - )   p l u t � t   q u e   l e   d � v e l o p p e u r )   e t   d ' I O D .   
 I l   e s t   f a i t   p o u r   l ' u t i l i s a t i o n   I O D   e t   S O L I D . 
 
 # # #   D R Y   ( D o n ' t   R e p e a t   Y o u r s e l f ) 
 C e   p r i n c i p e   d i t   q u ' i l   n e   f a u t   p a s   s e   r � p � t e r . 
 S i   u n   m o r c e a u   d e   c o d e   e s t   d � j �   � c r i t   p o u r   f a i r e   u n e   c e r t a i n e   t a c h e ,   a l o r s   i l   f a u t   l e   r � u t i l i s e r   d a n s   l e   r e s t e   d u   p r o g r a m m e . 
 
 D R Y   p e r m e t   d e   g a g n e r   d u   t e m p s   m a i s   a u s s i   d e   r e n d r e   l e   c o d e   p l u s   c o n s i s t a n t   e t   d e   f a c i l i t e r   l a   c o r r e c t i o n   d ' � v e n t u e l s   b o g u e s . 
 
 I l   v a   d e   p a i r   a v e c   l e s   p r i n c i p e s   d u   S O L I D   e t   d e   L ' I O D .   R e s p e c t e r   l e   S O L I D   e t   l ' I O D   p e r m e t   l a   r � u t i l i s a t i o n   d u   c o d e   p l u s   s i m p l e m e n t . 
 
 # # #   K I S S   ( K e e p   i t   s i m p l e ,   s t u p i d ) 
 R e s t e   s i m p l e   e t   s t u p i d e . 
 
 C e   p r i n c i p e   s t i p u l e   q u ' i l   e s t   p r � f � r a b l e   d ' a v o i r   u n   c o d e   s i m p l e   e t   f a c i l e   �   c o m p r e n d r e . 
 
 L e   S O L I D ,   I O D   e t   D R Y   p e r m e t t e n t   d e   r e n d r e   e n   g � n � r a l   l e   c o d e   p l u s   s i m p l e   e t   l i s i b l e . 
 
 U n   c o d e   t r o p   c o m p l e x e ,   o �   l e s   [ e n t i t � s   a p p l i c a t i v e s ] ( L e x i q u e . m d # e n t i t e s - a p p l i c a t i v e - )   o n t   p l u s i e u r s   r e s p o n s a b i l i t � s ,   e s t   p l u s   d i f f i c i l e   a   m a i n t e n i r   e t   a   f a i r e   � v o l u e r . 
 
 # # #   F o n c t i o n n e l   v s   T e c h n i q u e 
 P r i n c i p e   t r o p   s o u v e n t   o u b l i �   :   V o u s   n e   c o d e z   p a s   p o u r   v o u s ,   v o t r e   c o d e   n ' e s t   p a s   p o u r   v o u s   n i   �   v o u s   m a i s   a u   c l i e n t . 
 E t   * * l e   c l i e n t   n e   p a r l e   p a s   t e c h n i q u e * * . 
 
 S i   o n   v o u s   v e n d   u n   m e u b l e   e n   p a r l a n t   q u ' a v e c   d e s   t e r m e s   d e   l ' i n d u s t r i a l i s a t i o n   d e   l a     m e n u i s e r i e ,   i l   y   a   d e   g r a n d e   c h a n c e   q u e   v o u s   n e   c o m p r e n e z   p a s   t o u t . 
 
 L e s   f o n c t i o n n e l s   s o n t   l e s   p e r s o n n e s   q u i   n e   s o n t   p a s   t e c h n i q u e s   e t   q u i   p o s s � d e n t   l e   b e s o i n . 
 P a r   e x e m p l e   l e s   c l i e n t s ,   l e s   c h e f s   d e   p r o j e t s ,   l e s   p r o d u c t   o w n e r s ,   l e s   c o m m e r c i a u x ,   . . . 
 I l s   o n t   l e u r s   l a n g u a g e s   e t   n e   c o m p r e n n e n t   p a s   l e s   t e r m e s   t e c h n i q u e s   c o m m e   C R U D ,   S e r v i c e s ,   . . . 
 O u   p i r e . . .   I l s   o n t   d ' a u t r e   d � f i n i t i o n s   p o u r   c e s   t e r m e s . 
 
 L e s   t e c h n i q u e s   ( v o u s )   s o n t   l e s   p e r s o n n e s   q u i   p r o d u i s e n t   l e   p r o d u i t .   
 I l s   o n t   l e u r s   t e r m e s ,   s e   c o m p r e n n e n t   p l u s   o u   m o i n s   b i e n   e n t r e   e u x . 
 
 L ' u t i l i s a t i o n   d e   t e r m e s   t e c h n i q u e s   d a n s   l e s   p r � s e n t a t i o n s ,   l e s   r � u n i o n s   e t   m � m e   d a n s   l e   p r o d u i t s 
 ( l e   c o d e   o u   l a   d o c u m e n t a t i o n )   c o u p e   l a   d i s c u s s i o n   a v e c   l a   p a r t i e   f o n c t i o n n e l   d u   p r o j e t   e t 
 d o n c   p e u t   c r � e r   d e s   i n c o m p r � h e n s i o n s   a m e n a n t   d e s   e r r e u r s   e t   u n e   p e r t e   d e   t e m p s . 
 
 I l   f a u t   d o n c   _ _ m � m e   d a n s   l e   c o d e _ _   u t i l i s e r   l e   v o c a b u l a i r e   f o n c t i o n n e l .   
 C e l u i   d u   m e t i e r ,   c e l u i   p o u r   q u i   n o u s   p r o d u i s o n s   e t   n o n   n o t r e   l a n g u a g e   b a r b a r e . 
 
 S i   l e s   f o n c t i o n n e l s   p a r l e n t   e n   F r a n � a i s ,   n o u s   d � v e l o p p o n s   e n   F r a n � a i s   p o u r   p o u v o i r 
 u t i l i s e r   l e   m � m e   l e x i q u e   t o u t   a u   l o n g   d e   l a   p r o d u c t i o n   d u   p r o j e t . 
 
 # #   C o n c l u s i o n 
 L e s   d � v e l o p p e u r s   o n t   t e n d a n c e s   �   f a i r e   a u   p l u s   v i t e   s a n s   r � f l � c h i r   �   c r � e r   u n e   s t r u c t u r e   d e   c o d e   � v o l u t i f   e t   * f u t u r e   p r o o f * . 
 
 C e l a   e n t r a i n e   u n e   d i f f i c u l t �   �   r e n d r e   m a i n t e n a b l e   n o t r e   c o d e   s u r   l e   l o n g   t e r m e . 
 
 E n   a y a n t   e n   t � t e   l e s   p r i n c i p e s   d e   S O L I D ,   I O D ,   D R Y ,   K I S S   e t   F o n c t i o n n e l   v s   T e c h n i q u e   n o u s   p o u v o n s   m i e u x   s t r u c t u r e r   n o t r e   c o d e   e t   l e   r e n d r e   p l u s   m a i n t e n a b l e . 
 
 U n   c o d e   m a l   r � f l � c h i s   v i e i l l i t   _ _ T R E S   M A L _ _   e t   e n t r a i n e   b e a u c o u p   d e   p r o b l � m e s   p a r   l e   f u t u r   ( d e t t e   t e c h n i q u e )   !   
 
 S t r u c t u r e z   v o t r e   c o d e   p o u r   q u ' i l   s o i t   d u r ,   s e c  �=ܪ   e t   a v e c   u n   b i s o u  'd . 
 
 C e l a   � t a n t   d i t ,   c e   n e   s o n t   q u e   d e s   p r i n c i p e s   q u i   n e   p e u v e n t   p a s   � t r e   t o u j o u r s   s u i v i t   a   l a   l e t t r e . 
 I l s   d o i v e n t   � t r e   v u s   c o m m e   d e s   c o n c e p t s   a   a v o i r   e n   t � t e   l o r s   d u   d � v e l o p p e m e n t   d ' u n   p r o j e t . 
 
 
 
  