//constructor.txt  index.html  text123.txt
public class constructor{
  String name;
  long phone;
  String email;
  String qualfication;
  String workexpereince;
  String address;
  
  public DoctorConstructor(){
   System.out.println("default constructor");
  }
  
  public DoctorConstructorDemo(String n, long p,String e,String q,String we,String ad){
    name = n;
	phone = p;
	email = e;
	qualfication = q;
	workexpereince = we;
	address = ad;
  }
}
  public static void main(String args[]){
    DoctorConstructor dc1 = new DoctorConstructor();
	 System.out.println(dc1.name);
	 System.out.println(dc1.phone);
	 System.out.println(dc1.email);
	 System.out.println(dc1.qualfication);
	 System.out.println(dc1.workexpereince);
	 System.out.println(dc1.address);
	 
	DoctorConstructor dc2 = new DoctorConstructor("arun",807753994251L,"arun123@gmail.com","mbbs,ms in neruo surgery in cambridge","4years","malaysian township beside domains pizaa kondapur hyderabad");
	 System.out.println(dc2.name);
	 System.out.println(dc2.phone);
	 System.out.println(dc2.email);
	 System.out.println(dc2.qualfication);
	 System.out.println(dc2.workexpereince);
	 System.out.println(dc2.address);
	
	}
   }

