# 677A-VANYA-AND-FENCE
#include <bits/stdc++.h>
using namespace std;

int main() {
    int no_of_friends, height_of_fence;
    cin >> no_of_friends >> height_of_fence;

    int road_width = 0;
    for (int i = 0; i < no_of_friends; i++) {
        int individual_height;
        cin >> individual_height;

        if (individual_height > height_of_fence) {
            road_width += 2;
        } else {
            road_width += 1;
        }
    }

    cout << road_width << endl;
    return 0;
}
