# GITCHECK
HELLO
package polymorphisem;

public class AcRemote implements RemoteControll {
    @Override
    public void enable(boolean enable) {
        if (enable) {
            System.out.println("Ac is on ");
        } else {
            System.out.println("Ac is off");

        }
    }
}
