# package 123123;
public class RoundRobin {
	private Process [] processes;
	private int capacity;
	public RoundRobin(int capacity){
		this.capacity = capacity;
		processes = new Process [capacity];
	}

	void.start  (){
		for (int i = 0; i<processes.length; i++) {
			System.out.println(processes[0].getName());
			
		}
	}
	double getAvgTime () {
	return processes[0].getArr_time() / processes.length;	
	}
	public static void main (String [] args){
		RoundRobin roundRobin = new RoundRobin (capacity 5);
		roundRobin.processes[0]=new processes(name; "A", arr_time 0, burst_time 3);
		roundRobin.start();
		roundRobin.getAvgime();
		}
}
