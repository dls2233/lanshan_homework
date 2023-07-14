# 蓝山暑假考核作业第一次：<br>
总结：1.java八大类型byte short int long float doule char boolen,注意强制类型转换时的类型提升<br>
      short，byte，char<int<long<float<double<br>
      2.包装类注意自动装箱与自动拆箱，以及与String类型的转换即可<br>
      3.static静态修饰符，不需使用对象，可直接类名.直接访问<br>
        final不可变修饰符，被final修饰的变量不可改变，方法不可重写，类不可被继承，且往往与static<br>
        搭配使用<br>
      4.类的继承优点：实现代码重复利用，提高开发效率，子类都可得到父类的变量与方法，且可有自己独<br>
        立的变量与方法，同时也可以重写父类的方法，提高对象的多样性也有时是为了改变方法的使用。例<br>
        如一个类中，一般需要重写toStrin，equal，hashcode等方法，toString不重写只会打印地址，无<br>
        法输出有效内容，不重写equals方法同样也无法将两个对象比较，需重写比较两对象的方法。
      5.权限修饰符：用于限定类和方法的访问范围<br>
        public：均可访问<br>
        protect：同一类中，同一包中其他子类，不同包中其他子类<br>
        缺省：同一类中，同一包中的不同子类<br>
        private：仅限同一包中<br>
      6。java其他运算符以及及条件选择，循环等均与c大致类似（ps：位运算）<br>
      7.java中的数组：<br>
        动态开辟内存：（重要）int[] arr=new int[n]<br>
        静态开辟内存：int[] arr= new int[n]{a,b,c,...}<br>
        （二维数组同理）<br>
        
